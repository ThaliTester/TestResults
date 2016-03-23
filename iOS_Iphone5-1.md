#### Test 63848581b00dd7c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9B251601-5EEC-4901-90F9-63E2CCAB8B45/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/9B251601-5EEC-4901-90F9-63E2CCAB8B45/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55242"
,(lldb)     command script import "/tmp/9B251601-5EEC-4901-90F9-63E2CCAB8B45/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 13:02:59.960 ThaliTest[1553:3734573] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D20501F-E28A-4813-A65D-7E3EA008A343/Library/Cookies/Cookies.binarycookies
,2016-03-23 13:03:00.548 ThaliTest[1553:3734573] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 13:03:00.550 ThaliTest[1553:3734573] Multi-tasking -> Device: YES, App: YES
,2016-03-23 13:03:00.568 ThaliTest[1553:3734573] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 13:03:02.859 ThaliTest[1553:3734573] Using UIWebView
,2016-03-23 13:03:02.863 ThaliTest[1553:3734573] [CDVTimer][handleopenurl] 0.317991ms
,2016-03-23 13:03:02.869 ThaliTest[1553:3734573] [CDVTimer][intentandnavigationfilter] 5.298972ms
2016-03-23 13:03:02.870 ThaliTest[1553:3734573] [CDVTimer][gesturehandler] 0.257015ms
2016-03-23 13:03:02.870 ThaliTest[1553:3734573] [CDVTimer][TotalPluginS,tartup] 6.963968ms
,2016-03-23 13:03:11.989 ThaliTest[1553:3734573] Resetting plugins due to page load.
,2016-03-23 13:03:15.887 ThaliTest[1553:3734573] Finished load of: file:///var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/index.html
,2016-03-23 13:03:16.096 ThaliTest[1553:3734573] JXcore Cordova plugin initializing
,2016-03-23 13:03:16.099 ThaliTest[1553:3734794] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 13:03:32.749 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:03:32.750 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:03:32.751 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:03:32.754 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6E8443F0-70E4-4E76-A259-18FDD5E2D23E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 13:03:46.355 ThaliTest[1553:3734573] THREAD WARNING: ['JXcore'] took '12903.933105' ms. Plugin should use a background thread.
,2016-03-23 13:03:46.356 ThaliTest[1553:3734732] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51197
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51199
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
,DEBUG createNativeListener: listening 51202
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
,DEBUG createNativeListener: listening 51206
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
,DEBUG createNativeListener: listening 51211
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
,DEBUG createNativeListener: listening 51215
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
,DEBUG createNativeListener: listening 51219
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
,DEBUG createNativeListener: listening 51223
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
,DEBUG createNativeListener: listening 51227
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
,DEBUG createNativeListener: listening 51279
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
,DEBUG createNativeListener: listening 51283
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
ok 87 error should be null
,# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51295
,2016-03-23 13:06:23.000 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:23.002 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-23 13:06:23.007 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:23.008 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-23 13:06:23.175 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:23.175 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:23.175 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:06:23.176 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:23.177 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51297
,2016-03-23 13:06:23.511 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
,2016-03-23 13:06:23.513 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:23.515 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-23 13:06:23.562 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:23.565 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-23 13:06:25.838 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:25.839 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:25.839 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:06:25.839 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
2016-03-23 13:06:25.839 ThaliTest[1553:3734794] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:25.841 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51299
,2016-03-23 13:06:28.486 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:28.488 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:1
,2016-03-23 13:06:28.488 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
,2016-03-23 13:06:28.489 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:1
2016-03-23 13:06:28.490 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-23 13:06:28.517 ThaliTest[1553:3734573] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:2
2016-03-23 13:06:28.518 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:28.519 ThaliTest[1553:3734794] THEM,ultipeerManager stopping peer
2016-03-23 13:06:28.520 ThaliTest[1553:3734794] multipeer manager: stop client timer
2016-03-23 13:06:28.520 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:2
2016-03-23 13:06:28.521 ThaliTest[,1553:3734794] multipeer manager: start client restart timer: 0x17eca630
2016-03-23 13:06:28.521 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:2
2016-03-23 13:06:28.521 ThaliTest[1553:3734794] jxcore: st,artUpdateAdvertisingAndListening: success
,2016-03-23 13:06:28.545 ThaliTest[1553:3734573] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:2
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-23 13:06:29.150 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:29.150 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:29.150 ThaliTest[1553:3734794] multipeer manager: stop client timer
20,16-03-23 13:06:29.150 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:06:29.151 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:29.152 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51304
,2016-03-23 13:06:32.304 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:32.304 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:32.304 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
,ok 107 error should be null
,2016-03-23 13:06:32.308 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:32.309 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:32.309 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-23 13:06:32.396 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:32.396 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:32.397 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:06:32.397 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:32.398 ThaliTest[1553,:3734794] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51306
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-23 13:06:34.880 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:34.880 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:34.881 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:06:34.881 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:34.882 ThaliTest[1553,:3734794] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51308
,2016-03-23 13:06:35.217 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
2016-03-23 13:06:35.218 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:35.220 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,2016-03-23 13:06:35.263 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:35.264 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:3
2016-03-23 13:06:35.264 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:3
2016-03-23 13:06:35.265 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
ok 119 advertising state matches
,# teardown
,2016-03-23 13:06:35.593 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:35.593 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:35.593 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:06:35.594 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
2016-03-23 13:06:35.594 ThaliTest[1553:3734794] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:35.595 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
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
,ok 125 error should be null
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
,2016-03-23 13:06:44.305 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
2016-03-23 13:06:44.305 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:44.307 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:44.308 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
,2016-03-23 13:06:44.309 ThaliTest[1553:3734794] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:44.310 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-23 13:06:46.846 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:46.847 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:46.849 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:46.849 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:46.849 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-23 13:06:47.607 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
2016-03-23 13:06:47.607 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:47.609 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
2016-03-23 13:06:47.611 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:47.612 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-23 13:06:48.458 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
2016-03-23 13:06:48.459 ThaliTest[1553:3734794] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
,2016-03-23 13:06:48.460 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:48.461 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:48.462 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:48.462 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-23 13:06:48.953 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:48.953 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:4
2016-03-23 13:06:48.954 ThaliTest[1553:3734794] multipeer m,anager: start client restart timer: 0x17eca630
2016-03-23 13:06:48.954 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:4
2016-03-23 13:06:48.954 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-23 13:06:48.955 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:48.956 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016,-03-23 13:06:48.956 ThaliTest[1553:3734794] multipeer manager: stop client timer
2016-03-23 13:06:48.956 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-23 13:06:49.707 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:49.708 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-23 13:06:49.709 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:49.710 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:0,6:49.710 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-23 13:06:50.109 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:50.109 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:5
2016-03-23 13:06:50.110 ThaliTest[1553:3734794] multipeer m,anager: start client restart timer: 0x17eca630
2016-03-23 13:06:50.110 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:5
2016-03-23 13:06:50.110 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-23 13:06:50.111 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:50.112 ThaliTest[1553:3734794] THEMultipeerManager stopping pee,r
2016-03-23 13:06:50.112 ThaliTest[1553:3734794] multipeer manager: stop client timer
2016-03-23 13:06:50.112 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:6
2016-03-23 13:06:50.113 ThaliTest[1553:3734794] multipeer mana,ger: start client restart timer: 0x17eca630
,2016-03-23 13:06:50.115 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:6
2016-03-23 13:06:50.116 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdv,ertisingAndListening twice without error
# teardown
,2016-03-23 13:06:50.314 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:06:50.316 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:50.317 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:50.318 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:50.318 ThaliTest[1553:3734794] multipeer manager: stop client timer
2016-03-23 13:06:50.319 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-23 13:06:50.739 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:50.740 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:06:50.740 ThaliTest[1553:3734794] multipeer m,anager: start client restart timer: 0x17eca630
2016-03-23 13:06:50.740 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:06:50.740 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-23 13:06:50.742 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-23 13:06:50.743 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:51.610 ThaliTest[1553:3734573] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,ok 153 peers must be an array
ok 154 peers must not be zero-length
,ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-23 13:06:51.986 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:06:51.987 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:51.989 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:51.989 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:06:51.990 ThaliTest[1553:3734794] multipeer manager: stop client timer
2016-03-23 13:06:51.990 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-23 13:06:52.729 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:52.729 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:8
2016-03-23 13:06:52.730 ThaliTest[1553:3734794] multipeer m,anager: start client restart timer: 0x17eca630
2016-03-23 13:06:52.730 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:8
2016-03-23 13:06:52.730 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-23 13:06:52.731 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-23 13:06:52.732 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 162 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:53.644 ThaliTest[1553:3734573] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:06:53.645 ThaliTest[1553:3734573] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F676A619-7581-458A-A82D-21194588BD7A:8","pleaseConnect":0}]
,2016-03-23 13:06:53.650 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:06:53.650 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:06:53.650 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:06:53.651 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7","pleaseConnect":0}]
,2016-03-23 13:06:54.034 ThaliTest[1553:3735158] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:06:54.035 ThaliTest[1553:3735158] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:06:54.035 ThaliTest[1553:3735158] client session: disconnect
,2016-03-23 13:06:54.035 ThaliTest[1553:3735158] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:06:54.037 ThaliTest[1553:3735158] client session: no connect callback (server initiated)
,2016-03-23 13:07:03.652 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 13:07:06.661 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:06.662 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:07:06.663 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:07:06.663 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:07:06.834 ThaliTest[1553:3735202] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:06.835 ThaliTest[1553:3735202] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:07:06.8,36 ThaliTest[1553:3735202] client session: disconnect
2016-03-23 13:07:06.836 ThaliTest[1553:3735202] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:06.836 ThaliTest[1553:3735202] client session: no connect callback (server initiated)
,2016-03-23 13:07:12.731 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:07:12.747 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:12.750 ThaliTest[1553:3734573] client: found updated peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8","pleaseConnect":0}]
,2016-03-23 13:07:16.664 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 13:07:19.672 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:19.672 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:07:19.673 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:07:19.673 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:07:20.103 ThaliTest[1553:3735202] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:20.104 ThaliTest[1553:3735202] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:07:20.1,04 ThaliTest[1553:3735202] client session: disconnect
,2016-03-23 13:07:20.104 ThaliTest[1553:3735202] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:07:20.107 ThaliTest[1553:3735202] client session: no connect callback (server initiated)
,2016-03-23 13:07:29.674 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 13:07:32.687 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:32.687 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:07:32.688 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:07:32.689 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:07:32.731 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:07:32.753 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:32.754 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:42.689 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 13:07:45.707 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:45.707 ThaliTest[1553:3734794] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:45.708 ThaliTest[1553:3734794] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 13:07:48.718 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:48.719 ThaliTest[1553:3734794] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:48.719 Thali,Test[1553:3734794] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 13:07:51.736 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:51.736 ThaliTest[1553:3734794] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:51.737 Thali,Test[1553:3734794] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 13:07:52.731 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:07:52.747 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:52.748 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:54.756 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:54.757 ThaliTest[1553:3734794] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:54.757 Thali,Test[1553:3734794] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 13:07:57.775 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:57.776 ThaliTest[1553:3734794] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:57.777 Thali,Test[1553:3734794] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 13:08:00.796 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:00.797 ThaliTest[1553:3734794] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:00.797 Thali,Test[1553:3734794] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-03-23 13:08:00.948 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:08:00.950 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:08:00.951 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:08:00.952 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:08:00.952 ThaliTest[1553:3734794] client session: disconnect
2016-03-23 1,3:08:00.952 ThaliTest[1553:3734794] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:00.953 ThaliTest[1553:3734794] multipeer manager: stop client timer
2016-03-23 13:08:00.953 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
,ok 165 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-23 13:08:05.119 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:08:05.119 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:08:05.120 ThaliTest[1553:3734794] multipeer m,anager: start client restart timer: 0x17eca630
2016-03-23 13:08:05.120 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:08:05.121 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
,ok 166 Can call startUpdateAdvertisingAndListening without error
2016-03-23 13:08:05.124 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"dis,coveryActive":true}
2016-03-23 13:08:05.125 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 167 Can call startListeningForAdvertisements without error
,2016-03-23 13:08:06.456 ThaliTest[1553:3734573] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:06.457 ThaliTest[1553:3734573] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
2016-03-23 13:08:06.458 ThaliTes,t[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:06.459 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:08:06.459 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:08:06.459 Tha,liTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:07.682 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:07.683 ThaliTest[1553:3734573] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:07.742 ThaliTest[1553:3735371] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:07.742 ThaliTest[1553:3735371] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
,2016-03-23 13:08:07.743 ThaliTest[1553:3735371] client session: disconnect
,2016-03-23 13:08:07.744 ThaliTest[1553:3735371] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:07.745 ThaliTest[1553:3735371] client session: no connect callback (server initiated)
,2016-03-23 13:08:11.209 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:11.209 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:11.210 ThaliTest[1553:3734573], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:14.360 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:14.361 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:14.361 ThaliTest[1553:3734573], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:16.460 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 13:08:17.573 ThaliTest[1553:3734573] multipeer session: reset timer
,2016-03-23 13:08:17.573 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:17.573 ThaliTest[1553:3734573] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to p,revious generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:19.470 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:19.471 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:08:19.472 ThaliTest[1553:3734794] client session: reverseConn,ect
2016-03-23 13:08:19.472 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:19.628 ThaliTest[1553:3735371] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:19.631 ThaliTest[1553:3735371] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:08:19.631 ThaliTest[1553:3735371] client session: disconnect
2016-03-23 13:08:19.631 ThaliTest[1553:3735371] client session:, stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:19.631 ThaliTest[1553:3735371] client session: no connect callback (server initiated)
,2016-03-23 13:08:20.694 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:20.694 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:20.694 ThaliTest[1553:3734573], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:23.862 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:23.863 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:23.863 ThaliTest[1553:3734573], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:25.121 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:08:25.140 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:25.142 ThaliTest[1553:3734573] client: found updated peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:08:27.008 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:27.008 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:27.008 ThaliTest[1553:3734573], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:29.473 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 13:08:30.156 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:30.156 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:30.156 ThaliTest[1553:3734573], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:32.483 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:32.484 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:08:32.485 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:08:32.485 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:32.777 ThaliTest[1553:3735371] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:32.777 ThaliTest[1553:3735371] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:08:32.7,77 ThaliTest[1553:3735371] client session: disconnect
2016-03-23 13:08:32.777 ThaliTest[1553:3735371] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:32.777 ThaliTest[1553:3735371] client session: no connect callback (server initiated)
,2016-03-23 13:08:33.622 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:33.622 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:33.622 ThaliTest[1553:3734573] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:36.903 ThaliTest[1553:3734573] multipeer session: reset timer
2016-03-23 13:08:36.903 ThaliTest[1553:3734573] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:08:36.903 ThaliTest[1553:3734573] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9 != 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7)
,2016-03-23 13:08:42.486 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 13:08:45.121 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:08:45.139 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:45.140 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:08:45.491 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:45.492 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:08:45.493 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:08:45.493 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:45.938 ThaliTest[1553:3735385] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:45.939 ThaliTest[1553:3735385] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:08:45.9,39 ThaliTest[1553:3735385] client session: disconnect
2016-03-23 13:08:45.939 ThaliTest[1553:3735385] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:45.939 ThaliTest[1553:3735385] client session: no connect callback (server initiated)
,2016-03-23 13:08:55.494 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 13:08:58.504 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:58.505 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:08:58.505 ThaliTest[1553:3734794] client session: reverseConn,ect
2016-03-23 13:08:58.506 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:59.054 ThaliTest[1553:3735385] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:59.055 ThaliTest[1553:3735385] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:08:59.0,55 ThaliTest[1553:3735385] client session: disconnect
2016-03-23 13:08:59.055 ThaliTest[1553:3735385] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:08:59.055 ThaliTest[1553:3735385] client session: no connect callback (server initiated)
,2016-03-23 13:09:05.121 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:09:05.135 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:05.143 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:09:08.507 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 13:09:11.515 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:11.515 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:09:11.516 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:09:11.516 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:12.280 ThaliTest[1553:3735385] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:12.282 ThaliTest[1553:3735385] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:09:12.2,82 ThaliTest[1553:3735385] client session: disconnect
2016-03-23 13:09:12.283 ThaliTest[1553:3735385] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:12.283 ThaliTest[1553:3735385] client session: no connect callback (server initiated)
,2016-03-23 13:09:21.517 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 13:09:24.531 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:24.532 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:09:24.533 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:09:24.533 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:24.790 ThaliTest[1553:3735541] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:24.792 ThaliTest[1553:3735541] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:09:24.7,92 ThaliTest[1553:3735541] client session: disconnect
2016-03-23 13:09:24.792 ThaliTest[1553:3735541] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:24.792 ThaliTest[1553:3735541] client session: no connect callback (server initiated)
,2016-03-23 13:09:25.121 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:09:25.140 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:25.142 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:09:34.533 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 13:09:37.545 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:37.546 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:09:37.546 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:09:37.547 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:38.103 ThaliTest[1553:3735560] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:38.103 ThaliTest[1553:3735560] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:09:38.103 ThaliTest[1553:3735560] client session: disconnect
2016-03-23 13:09:38.103 ThaliTest[1553:3735560] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:38.105 ThaliTest[1553:3735560] client session: no connect callback (server initiated)
,2016-03-23 13:09:45.121 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:09:45.134 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:45.142 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:09:47.547 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 13:09:50.554 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:50.554 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:09:50.555 ThaliTest[1553:3734794] client session: reverseConnect
2016-03-23 13:09:50.556 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:09:51.074 ThaliTest[1553:3735560] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:51.074 ThaliTest[1553:3735560] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:09:51.074 ThaliTest[1553:3735560] client session: disconnect
,2016-03-23 13:09:51.074 ThaliTest[1553:3735560] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:09:51.076 ThaliTest[1553:3735560] client session: no connect callback (server initiated)
,2016-03-23 13:10:00.556 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 13:10:03.572 ThaliTest[1553:3734794] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:10:03.572 ThaliTest[1553:3734794] client: server will connect
2016-03-23 13:10:03.573 ThaliTest[1553:3734794] client session: reverseConn,ect
2016-03-23 13:10:03.573 ThaliTest[1553:3734794] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:10:04.044 ThaliTest[1553:3735611] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:10:04.044 ThaliTest[1553:3735611] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:10:04.0,44 ThaliTest[1553:3735611] client session: disconnect
,2016-03-23 13:10:04.045 ThaliTest[1553:3735611] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:10:04.046 ThaliTest[1553:3735611] client session: no connect callback (server initiated)
,2016-03-23 13:10:05.121 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:10:05.134 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:10:05.143 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:10:13.574 ThaliTest[1553:3734573] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 13:10:16.393 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-23 13:10:16.394 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
2016-03-23 13:10:16.395 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:16.396 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
,2016-03-23 13:10:16.396 ThaliTest[1553:3734794] multipeer manager: stop client timer
,2016-03-23 13:10:16.397 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-23 13:10:17.468 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:17.469 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:17.469 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:17.471 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-23 13:10:18.996 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:18.997 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:18.997 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:18.998 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-23 13:10:20.877 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:20.878 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:20.878 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:20.880 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51334
,2016-03-23 13:10:21.051 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:21.053 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-23 13:10:21.056 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:21.058 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-23 13:10:21.463 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:21.464 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:21.464 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:21.464 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:21.465 ThaliTest[1553,:3734794] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:21.831 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:21.832 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:21.832 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:21.834 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51336
,2016-03-23 13:10:22.035 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
2016-03-23 13:10:22.036 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:10:22.037 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
ok 175 no errors
,2016-03-23 13:10:22.039 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:10:22.041 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-23 13:10:22.428 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:22.428 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:22.428 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:22.429 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
2016-03-23 13:10:22.429 ThaliTest[1553:3734794] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:22.430 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:22.597 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:22.598 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:22.598 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:22.600 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51338
,2016-03-23 13:10:22.863 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:10:22.863 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:10
2016-03-23 13:10:22.864 ThaliTest[1553:3734794] multipeer ,manager: start client restart timer: 0x17eca630
2016-03-23 13:10:22.864 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:10
2016-03-23 13:10:22.864 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 177 no errors
2016-03-23 13:10:22.866 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:10:22.866 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:22.866 ThaliTest[1553:3734,794] multipeer manager: stop client timer
2016-03-23 13:10:22.866 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:11
2016-03-23 13:10:22.867 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630,
,2016-03-23 13:10:22.867 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:11
2016-03-23 13:10:22.872 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
,# teardown
,2016-03-23 13:10:22.889 ThaliTest[1553:3734573] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:10:23.192 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:23.192 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:23.192 ThaliTest[1553:3734794] multipeer manager: stop client timer
20,16-03-23 13:10:23.192 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:10:23.193 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:23.194 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:24.106 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:24.107 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:24.107 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:24.109 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51342
,2016-03-23 13:10:24.571 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:24.571 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:24.571 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 179 no errors
,2016-03-23 13:10:24.573 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:24.573 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:24.573 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
ok 180 still no errors
,# teardown
,2016-03-23 13:10:24.913 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:24.913 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:24.913 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:24.914 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:24.915 ThaliTest[1553,:3734794] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:25.064 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:25.064 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:25.065 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:25.067 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. can get the network status before starting
,ok 181 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-23 13:10:28.862 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:28.862 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:28.863 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:28.864 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 182 specific error expected
,# teardown
,# setup
,2016-03-23 13:10:30.275 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:30.276 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:30.276 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:30.277 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51344
,2016-03-23 13:10:30.415 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
2016-03-23 13:10:30.415 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:10:30.416 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
2016-03-23 13:10:30.417 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
201,6-03-23 13:10:30.417 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:12
2016-03-23 13:10:30.418 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:12
2016-03-23 13:10:30.418 Tha,liTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 183 connection to servers manager should succeed after starting
,ok 184 connection to router server should succeed after starting
,2016-03-23 13:10:30.464 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:30.465 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:30.465 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:30.465 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
2016-03-23 13:10:30.466 ThaliTest[1553:3734794] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:30.467 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 185 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 186 connection to servers manager should fail after stopping
,ok 187 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-23 13:10:36.130 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:36.130 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:36.131 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:36.132 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. make sure terminateConnection is properly hooked up
,ok 188 called with right arguments
,# teardown
,# setup
,2016-03-23 13:10:37.793 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:37.793 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:37.794 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:37.795 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. make sure terminateListener is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-23 13:10:38.226 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:38.227 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:38.227 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:38.229 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure we actually call kill connections properly
,2016-03-23 13:10:38.416 ThaliTest[1553:3734794] jxcore: killConnections
2016-03-23 13:10:38.416 ThaliTest[1553:3734794] jxcore: killConnections: badParam
,not ok 190 should not fail on iOS
  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-23 13:10:38.745 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:38.745 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:38.746 ThaliTest[1553:3,734794] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:38.747 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51351
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51350,"error":{}}
,2016-03-23 13:10:38.894 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:38.895 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:38.895 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:38.895 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:38.896 ThaliTest[1553,:3734794] jxcore: stopListeningForAdvertisements: success
,ok 191 failure reason is as expected
,ok 192 error description is as expected
,ok 193 must be stopped
,# teardown
,# setup
,2016-03-23 13:10:39.318 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:39.319 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:39.320 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:39.323 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51353
,ok 194 peerIdentifier matches
,ok 195 error description matches
,# teardown
,2016-03-23 13:10:39.567 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:39.567 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
2016-03-23 13:10:39.567 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:10:39.567 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:39.568 ThaliTest[1553,:3734794] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:39.689 ThaliTest[1553:3734794] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:39.691 ThaliTest[1553:3734794] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:39.692 ThaliTest[1553:3734794] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:39.694 ThaliTest[1553:3734794] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51355
,2016-03-23 13:10:39.826 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements
,2016-03-23 13:10:39.828 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 196 discoveryActive matches
,ok 197 advertisingActive matches
,2016-03-23 13:10:39.846 ThaliTest[1553:3734794] jxcore: startListeningForAdvertisements: success
,2016-03-23 13:10:39.848 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:39.849 ThaliTest[1553:3734794] THEMultipeerManager stopping peer
,2016-03-23 13:10:39.850 ThaliTest[1553:3734794] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:39.852 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements
,2016-03-23 13:10:39.855 ThaliTest[1553:3734794] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 198 discoveryActive matches
,ok 199 advertisingActive matches
,2016-03-23 13:10:39.862 ThaliTest[1553:3734794] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51357
,2016-03-23 13:10:39.874 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:10:39.875 ThaliTest[1553:3734794] server: starting 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:10:39.877 ThaliTest[1553:3734794] multipeer manager: start client restart timer: 0x17eca630
,2016-03-23 13:10:39.885 ThaliTest[1553:3734794] THEMultipeerManager initialized peer 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:10:39.886 ThaliTest[1553:3734794] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-23 13:10:41.124 ThaliTest[1553:3734573] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:10:42.000 ThaliTest[1553:3734573] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:10:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:10:59.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:10:59.905 ThaliTest[1553:3734573] client: found updated peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:11:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:11:19.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:11:19.905 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:11:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:11:39.902 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:11:39.904 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:11:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:11:59.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:11:59.905 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:12:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:12:19.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:12:19.904 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:12:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:12:39.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:12:39.900 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:12:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:12:59.902 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:12:59.903 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:13:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:13:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:13:39.895 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:13:39.895 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:13:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:13:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:13:59.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:14:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:14:19.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:14:19.898 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:14:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:14:39.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:14:39.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:14:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:14:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:14:59.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:15:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:15:19.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:15:19.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:15:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:15:39.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:15:39.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:15:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:15:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:15:59.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:16:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:16:19.895 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:16:19.897 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:16:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:16:39.894 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:16:39.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:16:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:16:59.897 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:16:59.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:17:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:17:19.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:17:19.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:17:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:17:39.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:17:39.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:17:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:17:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:17:59.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:18:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:18:19.895 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:18:19.895 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:18:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:18:39.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:18:39.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:18:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:18:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:18:59.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:19:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:19:19.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:19:19.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:19:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:19:39.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:19:39.897 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:19:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:20:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:20:19.895 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:20:19.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:20:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:20:39.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:20:39.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:20:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:20:59.897 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:20:59.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:21:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:21:19.895 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:21:19.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:21:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:21:39.895 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:21:39.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:21:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:21:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:21:59.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:22:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:22:19.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:22:19.897 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:22:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:22:39.898 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:22:39.898 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:22:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:22:59.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:22:59.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:23:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:23:19.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:23:19.897 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:23:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:23:39.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:23:39.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:23:59.882 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:23:59.895 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:23:59.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:24:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:24:19.896 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:24:19.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:24:39.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:24:39.894 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:24:39.896 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:24:59.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:25:19.883 ThaliTest[1553:3734573] multipeer manager: restart client
,2016-03-23 13:25:19.894 ThaliTest[1553:3734573] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:25:19.895 ThaliTest[1553:3734573] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13

```
