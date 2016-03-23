#### Test 63848581b00dd7c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/032121B8-0B61-4A45-8B0C-901EBFFF47A3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/032121B8-0B61-4A45-8B0C-901EBFFF47A3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55245"
,(lldb)     command script import "/tmp/032121B8-0B61-4A45-8B0C-901EBFFF47A3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 13:03:42.899 ThaliTest[2089:3563707] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E18398A2-25CF-4579-92A0-B7CD648F1B06/Library/Cookies/Cookies.binarycookies
,2016-03-23 13:03:43.322 ThaliTest[2089:3563707] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 13:03:43.323 ThaliTest[2089:3563707] Multi-tasking -> Device: YES, App: YES
,2016-03-23 13:03:43.342 ThaliTest[2089:3563707] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 13:03:45.371 ThaliTest[2089:3563707] Using UIWebView
,2016-03-23 13:03:45.378 ThaliTest[2089:3563707] [CDVTimer][handleopenurl] 0.538945ms
,2016-03-23 13:03:45.386 ThaliTest[2089:3563707] [CDVTimer][intentandnavigationfilter] 6.727993ms
,2016-03-23 13:03:45.386 ThaliTest[2089:3563707] [CDVTimer][gesturehandler] 0.361025ms
,2016-03-23 13:03:45.387 ThaliTest[2089:3563707] [CDVTimer][TotalPluginStartup] 9.311020ms
,2016-03-23 13:03:52.170 ThaliTest[2089:3563707] Resetting plugins due to page load.
,2016-03-23 13:03:55.989 ThaliTest[2089:3563707] Finished load of: file:///var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/index.html
,2016-03-23 13:03:56.173 ThaliTest[2089:3563707] JXcore Cordova plugin initializing
,2016-03-23 13:03:56.175 ThaliTest[2089:3563926] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 13:04:02.608 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:04:02.608 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:04:02.609 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:04:02.611 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/697D901C-89BC-47C4-A732-14CD9C0DB3FA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 13:04:07.805 ThaliTest[2089:3563707] THREAD WARNING: ['JXcore'] took '4918.494873' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51588
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51590
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
,DEBUG createNativeListener: listening 51593
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
,DEBUG createNativeListener: listening 51597
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
,DEBUG createNativeListener: listening 51602
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
,DEBUG createNativeListener: listening 51606
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
,DEBUG createNativeListener: listening 51610
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
,DEBUG createNativeListener: listening 51614
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 51618
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
,DEBUG createNativeListener: listening 51670
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
,DEBUG createNativeListener: listening 51674
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
,DEBUG createNativeListener: listening 51686
,2016-03-23 13:06:25.261 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:25.264 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-23 13:06:25.269 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:25.272 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-23 13:06:25.418 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:25.419 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:25.419 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:25.421 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:25.423 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51688
,2016-03-23 13:06:25.762 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:06:25.764 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:25.771 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-23 13:06:25.788 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:25.792 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-23 13:06:27.221 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:27.221 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:27.222 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:27.223 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,2016-03-23 13:06:27.226 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:27.229 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51690
,2016-03-23 13:06:29.653 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:29.654 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:1
,2016-03-23 13:06:29.656 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:06:29.656 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:1
,2016-03-23 13:06:29.657 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-23 13:06:29.690 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:29.691 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:29.692 ThaliTest[2089:3563926] multipeer manager: stop client timer
2016-03-23 13:06:29.692 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:2
2016-03-23 13:06:29.693 ThaliTest[2089:3563926] multipeer manager,: start client restart timer: 0x2029410
2016-03-23 13:06:29.693 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:2
2016-03-23 13:06:29.694 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-23 13:06:31.396 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:31.396 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:31.397 ThaliTest[2089:3563926] multipeer manager: stop client timer
2016-03-23 13:06:31.398 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:31.399 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:31.407 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51695
,2016-03-23 13:06:34.172 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:34.173 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:34.173 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,2016-03-23 13:06:34.179 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:34.180 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:34.180 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-23 13:06:34.636 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:34.636 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:34.637 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:34.639 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:34.641 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51697
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-23 13:06:37.157 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:37.158 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:37.158 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:37.159 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:37.162 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51699
,2016-03-23 13:06:37.472 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:06:37.473 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:37.476 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,2016-03-23 13:06:37.492 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:37.493 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:3
,2016-03-23 13:06:37.494 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:3
2016-03-23 13:06:37.495 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-23 13:06:37.866 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:37.867 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:37.868 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:06:37.869 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
2016-03-23 13:06:37.869 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:37.872 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
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
,2016-03-23 13:06:46.562 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:06:46.563 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:46.566 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:46.571 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,2016-03-23 13:06:46.571 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:46.576 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-23 13:06:49.260 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:49.262 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:49.265 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:49.265 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:49.266 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-23 13:06:49.832 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:06:49.832 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:49.835 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:49.838 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:49.841 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-23 13:06:50.793 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,2016-03-23 13:06:50.794 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:50.798 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-23 13:06:50.801 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:50.802 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:50.802 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-23 13:06:51.194 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:51.194 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:4
,2016-03-23 13:06:51.196 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:06:51.197 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:4
,2016-03-23 13:06:51.197 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:06:51.202 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:51.203 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:51.205 ThaliTest[2089:3563926] multipeer manager: stop client timer
2016-03-23 13:06:51.205 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-23 13:06:51.842 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:51.844 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:51.846 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:51.847 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:51.848 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-23 13:06:52.240 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:52.241 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:5
,2016-03-23 13:06:52.242 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:06:52.242 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:5
2016-03-23 13:06:52.243 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 147 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:06:52.247 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:52.247 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
2016-03-23 13:06:52.247 ThaliTest[2089:3563926] multipeer manager: stop client ti,mer
2016-03-23 13:06:52.248 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:6
2016-03-23 13:06:52.249 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,2016-03-23 13:06:52.249 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:6
2016-03-23 13:06:52.250 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 148 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-03-23 13:06:52.567 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:06:52.569 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:52.572 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:52.572 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:52.573 ThaliTest[2089:3563926] multipeer manager: stop client timer
,2016-03-23 13:06:52.573 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-23 13:06:52.985 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:52.985 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:06:52.987 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:06:52.988 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:06:52.988 T,haliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-23 13:06:52.996 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 13:06:53.000 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 152 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:53.854 ThaliTest[2089:3563707] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,ok 153 peers must be an array
,ok 154 peers must not be zero-length
,ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-23 13:06:54.039 ThaliTest[2089:3563707] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:06:54.231 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:06:54.234 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:54.236 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:54.237 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:06:54.238 ThaliTest[2089:3563926] multipeer manager: stop client timer
,2016-03-23 13:06:54.238 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-23 13:06:54.808 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:54.809 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:06:54.810 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:06:54.810 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:06:54.811 T,haliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:06:54.813 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 13:06:54.815 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 162 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:55.369 ThaliTest[2089:3563707] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:06:55.370 ThaliTest[2089:3563707] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7","pleaseConnect":0}]
,2016-03-23 13:06:55.373 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:06:55.375 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:06:55.375 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7","pleaseConnect":0}]
,2016-03-23 13:06:56.008 ThaliTest[2089:3564306] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
2016-03-23 13:06:56.008 ThaliTest[2089:3564306] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:06:56.009 ThaliTest[2089:3564306] client session: disconnect
,2016-03-23 13:06:56.009 ThaliTest[2089:3564306] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
2016-03-23 13:06:56.011 ThaliTest[2089:3564306] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:06:56.012 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 13:06:56.153 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:06:56.154 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:8","pleaseConnect":1}]
,2016-03-23 13:06:56.411 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:06:56.412 ThaliTest[2089:3563707] server: rejecting invitation from 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D due to previous generation (F676A619-7581-458A-A82D-21194588BD7A:8 != F676A619-7581-458A-A82D-21194588BD7A:7)
,2016-03-23 13:06:59.020 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:06:59.021 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:06:59.021 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:06:59.172 ThaliTest[2089:3564305] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
2016-03-23 13:06:59.172 ThaliTest[2089:3564305] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
,2016-03-23 13:06:59.173 ThaliTest[2089:3564305] client session: disconnect
2016-03-23 13:06:59.173 ThaliTest[2089:3564305] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:06:59.174 ThaliTest[2089:3564305] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:06:59.174 ThaliTest[2089:3564305] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 13:07:02.181 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:02.182 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:07:02.183 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:02.429 ThaliTest[2089:3564305] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:02.429 ThaliTest[2089:3564305] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
,2016-03-23 13:07:02.431 ThaliTest[2089:3564305] client session: disconnect
,2016-03-23 13:07:02.431 ThaliTest[2089:3564305] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:02.432 ThaliTest[2089:3564305] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:02.432 ThaliTest[2089:3564305] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 13:07:05.448 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:05.448 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:07:05.449 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:05.888 ThaliTest[2089:3564301] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:05.888 ThaliTest[2089:3564301] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:05.890 ThaliTest[2089:3564301] client session: disconnect
2016-03-23 13:07:05.890 ThaliTest[2089:3564301] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:05.891 ThaliTest[2089:3564301] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:05.891 ThaliTest[2089:3564301] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 13:07:08.897 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:08.898 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:07:08.899 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:09.050 ThaliTest[2089:3564309] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
2016-03-23 13:07:09.051 ThaliTest[2089:3564309] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:09.051 ThaliTest[2089:3564309] client session: disconnect
,2016-03-23 13:07:09.051 ThaliTest[2089:3564309] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:09.053 ThaliTest[2089:3564309] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:09.054 ThaliTest[2089:3564309] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 13:07:09.061 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:07:09.062 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
2016-03-23 13:07:09.062 ThaliTest[2089:3563707], server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:8","pleaseConnect":1}]
,2016-03-23 13:07:09.450 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:07:09.451 ThaliTest[2089:3563707] server: disconnecting to refresh session (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D)
,2016-03-23 13:07:09.451 ThaliTest[2089:3563707] server: rejecting invitation from 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D due to previous generation (F676A619-7581-458A-A82D-21194588BD7A:8 != F676A619-7581-458A-A82D-21194588BD7A:7)
,2016-03-23 13:07:12.071 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:12.072 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:07:12.072 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:12.262 ThaliTest[2089:3564306] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:12.263 ThaliTest[2089:3564306] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:12.264 ThaliTest[2089:3564306] client session: disconnect
,2016-03-23 13:07:12.264 ThaliTest[2089:3564306] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:12.265 ThaliTest[2089:3564306] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:12.265 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 13:07:14.812 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:07:14.825 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:07:14.826 ThaliTest[2089:3563707] client: found updated peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8","pleaseConnect":0}]
,2016-03-23 13:07:15.276 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:15.277 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:07:15.277 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:15.764 ThaliTest[2089:3564310] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
2016-03-23 13:07:15.764 ThaliTest[2089:3564310] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:15.765 ThaliTest[2089:3564310] client session: disconnect
,2016-03-23 13:07:15.765 ThaliTest[2089:3564310] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:15.767 ThaliTest[2089:3564310] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:15.767 ThaliTest[2089:3564310] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 13:07:18.775 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:18.777 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:07:18.777 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:19.006 ThaliTest[2089:3564306] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
2016-03-23 13:07:19.007 ThaliTest[2089:3564306] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
,2016-03-23 13:07:19.007 ThaliTest[2089:3564306] client session: disconnect
2016-03-23 13:07:19.007 ThaliTest[2089:3564306] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:19.008 ThaliTest[2089:3564306] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
,2016-03-23 13:07:19.009 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 13:07:22.020 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:22.021 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:07:22.022 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:22.220 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:07:22.220 ThaliTest[2089:3563707] server: disconnecting to refresh session (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D)
,2016-03-23 13:07:22.221 ThaliTest[2089:3563707] server: rejecting invitation from 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D due to previous generation (F676A619-7581-458A-A82D-21194588BD7A:8 != F676A619-7581-458A-A82D-21194588BD7A:7)
,2016-03-23 13:07:22.293 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:07:22.293 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
,2016-03-23 13:07:22.293 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:8","pleaseConnect":1}]
,2016-03-23 13:07:22.314 ThaliTest[2089:3564305] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:22.315 ThaliTest[2089:3564305] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:22.316 ThaliTest[2089:3564305] client session: disconnect
,2016-03-23 13:07:22.316 ThaliTest[2089:3564305] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:22.317 ThaliTest[2089:3564305] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:22.317 ThaliTest[2089:3564305] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 13:07:25.328 ThaliTest[2089:3563926] jxcore: connect 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
,2016-03-23 13:07:25.329 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:07:25.329 ThaliTest[2089:3563926] client session: stateChange:0->1 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:25.789 ThaliTest[2089:3564310] client session: not connected 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
2016-03-23 13:07:25.790 ThaliTest[2089:3564310] client session: onLinkFailure: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
2016-03-23 13:07:25.790 ThaliTest[2089:3564310] client session: disconnect
,2016-03-23 13:07:25.791 ThaliTest[2089:3564310] client session: stateChange:1->0 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:07:25.792 ThaliTest[2089:3564310] client session: fireConnectCallback: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D
,2016-03-23 13:07:25.792 ThaliTest[2089:3564310] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 13:07:34.812 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:07:34.825 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
2016-03-23 13:07:34.825 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:07:54.812 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:07:54.826 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:07:54.827 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:08:03.266 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:08:03.269 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:08:03.271 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:08:03.272 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:08:03.273 ThaliTest[2089:3563926] multipeer manager: stop client timer
2016-03-23 13:08:03.273 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
ok 165 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can shift large amounts of data
,2016-03-23 13:08:06.381 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:08:06.382 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:06.384 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,2016-03-23 13:08:06.386 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:08:06.393 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 166 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:08:06.398 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 13:08:06.400 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 167 Can call startListeningForAdvertisements without error
,2016-03-23 13:08:08.358 ThaliTest[2089:3563707] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:08.360 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:08:08.361 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:08.362 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:09.731 ThaliTest[2089:3563707] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:08:09.925 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:08:09.925 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:09.982 ThaliTest[2089:3564306] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:08:09.983 ThaliTest[2089:3564306] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:09.983 ThaliTest[2089:3564306] client session: disconnect
,2016-03-23 13:08:09.984 ThaliTest[2089:3564306] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:09.986 ThaliTest[2089:3564306] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:09.986 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 13:08:10.911 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:08:10.911 ThaliTest[2089:3563707] server: rejecting invitation from 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D due to previous generation (F676A619-7581-458A-A82D-21194588BD7A:9 != F676A619-7581-458A-A82D-21194588BD7A:8)
,2016-03-23 13:08:12.995 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:12.996 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:08:12.997 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:13.462 ThaliTest[2089:3564306] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:08:13.463 ThaliTest[2089:3564306] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:13.463 ThaliTest[2089:3564306] client session: disconnect
2016-03-23 13:08:13.465 ThaliTest[2089:3564306] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:08:13.465 ThaliTest[2089:3564306] client sess,ion: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:13.466 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 13:08:16.477 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:16.478 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:08:16.478 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:16.669 ThaliTest[2089:3564499] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:16.669 ThaliTest[2089:3564499] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:16.670 ThaliTest[2089:3564499] client session: disconnect
2016-03-23 13:08:16.671 ThaliTest[2089:3564499] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:16.672 ThaliTest[2089:3564499] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:16.672 ThaliTest[2089:3564499] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 13:08:19.685 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:19.686 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:19.687 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:19.843 ThaliTest[2089:3564481] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:08:19.843 ThaliTest[2089:3564481] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:19.844 ThaliTest[2089:3564481] client session: disconnect
,2016-03-23 13:08:19.845 ThaliTest[2089:3564481] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:19.847 ThaliTest[2089:3564481] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:19.847 ThaliTest[2089:3564481] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 13:08:21.848 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:08:21.848 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
,2016-03-23 13:08:21.848 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:22.773 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:08:22.774 ThaliTest[2089:3563707] server: disconnecting to refresh session (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D)
2016-03-23 13:08:22.774 ThaliTest[2089:3563707] server: rejecting invitation from 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D due to previous generation (F676A619-7581-458A-A82D-21194588BD7A:9 != F676A619-7581-458A-A82D-21194588BD7A:8)
,2016-03-23 13:08:22.861 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:22.862 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:22.862 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:22.965 ThaliTest[2089:3564306] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:22.965 ThaliTest[2089:3564306] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:22.967 ThaliTest[2089:3564306] client session: disconnect
,2016-03-23 13:08:22.967 ThaliTest[2089:3564306] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:22.968 ThaliTest[2089:3564306] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:22.969 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 13:08:25.979 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:25.980 ThaliTest[2089:3563926] client session: connect
2016-03-23 13:08:25.980 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:26.115 ThaliTest[2089:3564306] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:08:26.116 ThaliTest[2089:3564306] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:26.116 ThaliTest[2089:3564306] client session: disconnect
,2016-03-23 13:08:26.116 ThaliTest[2089:3564306] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:26.117 ThaliTest[2089:3564306] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:26.118 ThaliTest[2089:3564306] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 13:08:26.387 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:08:26.401 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
2016-03-23 13:08:26.402 ThaliTest[2089:3563707] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:29.132 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:29.133 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:29.133 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:29.278 ThaliTest[2089:3564475] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:08:29.279 ThaliTest[2089:3564475] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:29.279 ThaliTest[2089:3564475] client session: disconnect
2016-03-23 13:08:29.279 ThaliTest[2089:3564475] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:29.281 ThaliTest[2089:3564475] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:29.282 ThaliTest[2089:3564475] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 13:08:32.292 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:32.293 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:32.293 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:32.766 ThaliTest[2089:3564499] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:32.766 ThaliTest[2089:3564499] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:32.768 ThaliTest[2089:3564499] client session: disconnect
2016-03-23 13:08:32.768 ThaliTest[2089:3564499] client session:, stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:08:32.769 ThaliTest[2089:3564499] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:32.769 ThaliTest[2089:3564499] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 13:08:34.956 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:08:34.957 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
2016-03-23 13:08:34.958 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:35.672 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:08:35.673 ThaliTest[2089:3563707] server: disconnecting to refresh session (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D)
2016-03-23 13:08:35.673 ThaliTest[2089:3563707] server: rejecting invitation from 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D due to previous generation (F676A619-7581-458A-A82D-21194588BD7A:9 != F676A619-7581-458A-A82D-21194588BD7A:8)
,2016-03-23 13:08:35.780 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:35.780 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:35.781 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:35.879 ThaliTest[2089:3564499] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:08:35.880 ThaliTest[2089:3564499] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:35.881 ThaliTest[2089:3564499] client session: disconnect
2016-03-23 13:08:35.882 ThaliTest[2089:3564499] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:35.883 ThaliTest[2089:3564499] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:35.883 ThaliTest[2089:3564499] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 13:08:38.888 ThaliTest[2089:3563926] jxcore: connect 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:38.890 ThaliTest[2089:3563926] client session: connect
,2016-03-23 13:08:38.890 ThaliTest[2089:3563926] client session: stateChange:0->1 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:39.205 ThaliTest[2089:3564475] client session: not connected 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:08:39.206 ThaliTest[2089:3564475] client session: onLinkFailure: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
2016-03-23 13:08:39.206 ThaliTest[2089:3564475] client session: disconnect
2016-03-23 13:08:39.206 ThaliTest[2089:3564475] client session: stateChange:1->0 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:39.207 ThaliTest[2089:3564475] client session: fireConnectCallback: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:08:39.209 ThaliTest[2089:3564475] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 13:08:46.387 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:08:46.400 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:46.401 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:08:48.121 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:08:48.122 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
2016-03-23 13:08:48.122 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:09:01.287 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:09:01.287 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
,2016-03-23 13:09:01.288 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:09:06.387 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:09:06.401 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
2016-03-23 13:09:06.401 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:09:14.470 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:09:14.470 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
2016-03-23 13:09:14.471 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:09:26.387 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:09:26.402 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
2016-03-23 13:09:26.402 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:09:26.978 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:09:26.979 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
,2016-03-23 13:09:26.979 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:09:40.336 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:09:40.337 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
2016-03-23 13:09:40.337 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:09:46.387 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:09:46.404 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
2016-03-23 13:09:46.404 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:09:53.275 ThaliTest[2089:3563707] multipeer session: reset timer
,2016-03-23 13:09:53.276 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
,2016-03-23 13:09:53.276 ThaliTest[2089:3563707] server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:10:06.227 ThaliTest[2089:3563707] multipeer session: reset timer
2016-03-23 13:10:06.228 ThaliTest[2089:3563707] server: disconnecting to refresh session (6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D)
2016-03-23 13:10:06.228 ThaliTest[2089:3563707], server: rejecting invitation for lexical ordering 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D
,2016-03-23 13:10:06.387 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:10:06.401 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
2016-03-23 13:10:06.402 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:10:16.668 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:10:16.670 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:10:16.673 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:16.674 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:16.675 ThaliTest[2089:3563926] multipeer manager: stop client timer
,2016-03-23 13:10:16.676 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-23 13:10:19.435 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:19.437 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:19.437 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:19.440 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-23 13:10:21.256 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:21.257 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:21.259 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:21.262 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-23 13:10:22.993 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:22.994 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:22.996 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:22.999 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51736
,2016-03-23 13:10:23.305 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:23.307 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-23 13:10:23.310 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:23.312 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-23 13:10:23.797 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:23.797 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:23.798 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:23.799 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:23.802 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:24.086 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:24.087 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:24.089 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:24.092 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51738
,2016-03-23 13:10:24.292 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:10:24.293 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:10:24.301 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 175 no errors
,2016-03-23 13:10:24.305 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:10:24.307 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-23 13:10:24.679 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:24.680 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:24.680 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:24.681 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,2016-03-23 13:10:24.683 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:24.686 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:24.851 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:24.852 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:24.853 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:24.856 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51740
,2016-03-23 13:10:25.117 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:10:25.118 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:10
,2016-03-23 13:10:25.119 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:10:25.119 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:10
2016-03-23 13:10:25.120 ,ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,ok 177 no errors
,2016-03-23 13:10:25.123 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:10:25.123 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
2016-03-23 13:10:25.124 ThaliTest[2089:3563926] multipeer manager: stop client timer
2016-03-23 13:10:25.124 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:11
,2016-03-23 13:10:25.126 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
2016-03-23 13:10:25.127 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:11
2016-03-23 13:10:25.127 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
,# teardown
,2016-03-23 13:10:25.440 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:25.441 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:25.441 ThaliTest[2089:3563926] multipeer manager: stop client timer
,2016-03-23 13:10:25.444 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:25.445 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:25.447 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:26.192 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:26.193 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:26.194 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:26.197 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51744
,2016-03-23 13:10:26.885 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:26.885 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
2016-03-23 13:10:26.886 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 179 no errors
,2016-03-23 13:10:26.889 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:26.890 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:26.891 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,ok 180 still no errors
,# teardown
,2016-03-23 13:10:27.151 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:27.152 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:27.152 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:27.153 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:27.156 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:27.325 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:27.327 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:27.328 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:27.331 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. can get the network status before starting
,ok 181 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-23 13:10:31.495 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:31.496 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:31.497 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:31.500 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 182 specific error expected
,# teardown
,# setup
,2016-03-23 13:10:32.418 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:32.419 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:32.420 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:32.423 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51746
,2016-03-23 13:10:32.649 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:10:32.650 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:10:32.653 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,2016-03-23 13:10:32.657 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:10:32.658 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:12
,2016-03-23 13:10:32.659 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:12
,2016-03-23 13:10:32.661 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 183 connection to servers manager should succeed after starting
,ok 184 connection to router server should succeed after starting
,2016-03-23 13:10:32.712 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:32.712 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:32.714 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:32.716 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,2016-03-23 13:10:32.718 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:32.723 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 185 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 186 connection to servers manager should fail after stopping
,ok 187 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-23 13:10:34.544 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:34.545 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:34.547 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:34.550 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. make sure terminateConnection is properly hooked up
,ok 188 called with right arguments
,# teardown
,# setup
,2016-03-23 13:10:40.052 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:40.053 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:40.054 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:40.057 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. make sure terminateListener is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-23 13:10:40.523 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:40.524 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:40.525 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:40.528 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure we actually call kill connections properly
,2016-03-23 13:10:40.672 ThaliTest[2089:3563926] jxcore: killConnections
2016-03-23 13:10:40.672 ThaliTest[2089:3563926] jxcore: killConnections: badParam
,not ok 190 should not fail on iOS
,  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-23 13:10:40.994 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:40.995 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:40.997 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:41.001 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51753
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51752,"error":{}}
,2016-03-23 13:10:41.158 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:41.158 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:41.160 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:41.161 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:41.164 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,ok 191 failure reason is as expected
,ok 192 error description is as expected
,ok 193 must be stopped
,# teardown
,# setup
,2016-03-23 13:10:41.567 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:41.569 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:41.570 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:41.572 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51755
,ok 194 peerIdentifier matches
,ok 195 error description matches
,# teardown
,2016-03-23 13:10:41.816 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:41.816 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
,2016-03-23 13:10:41.817 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:41.818 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:41.821 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:41.932 ThaliTest[2089:3563926] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:41.933 ThaliTest[2089:3563926] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:41.934 ThaliTest[2089:3563926] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:41.937 ThaliTest[2089:3563926] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51757
,2016-03-23 13:10:42.082 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements
,2016-03-23 13:10:42.083 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 196 discoveryActive matches
ok 197 advertisingActive matches
2016-03-23 13:10:42.088 ThaliTest[2089:3563926] jxcore: startListeningForAdvertisements: success
,2016-03-23 13:10:42.091 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:42.092 ThaliTest[2089:3563926] THEMultipeerManager stopping peer
2016-03-23 13:10:42.092 ThaliTest[2089:3563926] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:10:42.093 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements
,2016-03-23 13:10:42.094 ThaliTest[2089:3563926] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 198 discoveryActive matches
,ok 199 advertisingActive matches
,2016-03-23 13:10:42.101 ThaliTest[2089:3563926] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51759
,2016-03-23 13:10:42.115 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:10:42.116 ThaliTest[2089:3563926] server: starting F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:10:42.117 ThaliTest[2089:3563926] multipeer manager: start client restart timer: 0x2029410
,2016-03-23 13:10:42.117 ThaliTest[2089:3563926] THEMultipeerManager initialized peer F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:10:42.118 ThaliTest[2089:3563926] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-23 13:10:42.783 ThaliTest[2089:3563707] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:10:44.062 ThaliTest[2089:3563707] client: found new peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:11:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:11:02.132 ThaliTest[2089:3563707] client: found updated peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:11:02.132 ThaliTest[2089:3563707] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:11:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:11:22.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:11:22.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:11:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:11:42.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:11:42.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:12:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:12:02.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:12:02.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:12:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:12:22.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:12:22.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:12:42.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:12:43.122 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:12:43.123 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:13:02.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:13:02.131 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:13:02.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:13:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:13:22.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:13:22.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:13:42.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:13:42.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:13:42.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:14:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:14:02.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:14:02.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:14:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:14:22.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:14:22.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:14:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:14:42.134 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:14:42.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:15:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:15:02.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:15:02.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:15:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:15:22.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:15:22.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:15:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:15:42.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:15:42.134 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:16:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:16:02.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:16:02.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:16:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:16:22.134 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:16:22.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:16:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:16:42.135 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:16:42.136 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:17:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:17:02.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:17:02.135 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:17:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:17:22.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:17:22.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:17:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:17:42.135 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:17:42.135 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:18:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:18:02.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:18:02.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:18:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:18:22.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:18:22.135 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:18:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:18:42.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:18:42.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:19:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:19:02.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:19:02.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:19:22.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:19:22.135 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:19:22.135 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:19:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:19:42.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:19:42.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:20:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:20:02.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:20:02.135 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:20:22.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:20:22.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:20:22.134 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:20:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:20:42.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:20:42.136 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:21:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:21:02.135 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:21:02.135 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:21:22.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:21:22.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:21:22.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:21:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:21:42.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:21:42.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:22:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:22:02.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:22:02.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:22:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:22:22.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:22:22.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:22:42.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:22:42.133 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:22:42.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:23:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:23:02.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:23:02.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:23:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:23:22.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:23:22.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:23:42.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:23:42.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:23:42.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:24:02.118 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:24:02.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
2016-03-23 13:24:02.132 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:24:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:24:22.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:24:22.134 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:24:42.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:24:42.132 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:24:42.134 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:25:02.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:25:02.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:25:02.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
,2016-03-23 13:25:22.119 ThaliTest[2089:3563707] multipeer manager: restart client
,2016-03-23 13:25:22.131 ThaliTest[2089:3563707] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:25:22.133 ThaliTest[2089:3563707] client: found existing peer: 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13

```
