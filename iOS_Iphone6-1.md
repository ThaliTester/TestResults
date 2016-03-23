#### Test 63848581358a1d8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4218B8BE-B1E8-4E6F-A276-32DDD5C45908/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4218B8BE-B1E8-4E6F-A276-32DDD5C45908/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55182"
,(lldb)     command script import "/tmp/4218B8BE-B1E8-4E6F-A276-32DDD5C45908/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 11:45:36.803 ThaliTest[2011:3474885] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F684304-6601-42E1-B3D9-E0E3D508B29A/Library/Cookies/Cookies.binarycookies
,2016-03-23 11:45:37.228 ThaliTest[2011:3474885] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 11:45:37.230 ThaliTest[2011:3474885] Multi-tasking -> Device: YES, App: YES
,2016-03-23 11:45:37.255 ThaliTest[2011:3474885] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 11:45:39.103 ThaliTest[2011:3474885] Using UIWebView
,2016-03-23 11:45:39.111 ThaliTest[2011:3474885] [CDVTimer][handleopenurl] 0.746012ms
,2016-03-23 11:45:39.118 ThaliTest[2011:3474885] [CDVTimer][intentandnavigationfilter] 7.164001ms
2016-03-23 11:45:39.119 ThaliTest[2011:3474885] [CDVTimer][gesturehandler] 0.380993ms
2016-03-23 11:45:39.120 ThaliTest[2011:3474885] [CDVTimer][TotalPluginStartup] 9.974003ms
,2016-03-23 11:45:46.433 ThaliTest[2011:3474885] Resetting plugins due to page load.
,2016-03-23 11:45:49.771 ThaliTest[2011:3474885] Finished load of: file:///var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/index.html
,2016-03-23 11:45:50.015 ThaliTest[2011:3474885] JXcore Cordova plugin initializing
,2016-03-23 11:45:50.017 ThaliTest[2011:3475110] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 11:45:57.279 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:45:57.280 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:45:57.280 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:45:57.282 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/35BA7175-4266-4545-8282-85308B8083F9/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 11:46:03.175 ThaliTest[2011:3474885] THREAD WARNING: ['JXcore'] took '5574.296143' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50576
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50578
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
,DEBUG createNativeListener: listening 50581
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
,DEBUG createNativeListener: listening 50585
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
,DEBUG createNativeListener: listening 50590
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
,DEBUG createNativeListener: listening 50594
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
,DEBUG createNativeListener: listening 50598
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
,DEBUG createNativeListener: listening 50602
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
,DEBUG createNativeListener: listening 50606
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
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: listening 50658
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
,DEBUG createNativeListener: listening 50662
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
,DEBUG createNativeListener: listening 50674
,2016-03-23 11:48:04.455 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:04.459 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-23 11:48:04.464 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:04.466 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-23 11:48:04.597 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:04.598 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:04.598 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:04.601 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:04.603 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50676
,2016-03-23 11:48:04.934 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:04.936 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:04.938 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-23 11:48:04.954 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:48:04.956 ThaliTest[2011:34751,10] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
,# teardown
,2016-03-23 11:48:05.297 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:05.297 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:05.298 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 11:48:05.298 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:05.299 ThaliTest[2011:3475110] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:05.304 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50678
,2016-03-23 11:48:07.946 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:07.947 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:1
2016-03-23 11:48:07.948 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
,2016-03-23 11:48:07.949 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:1
,2016-03-23 11:48:07.950 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-23 11:48:07.968 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:07.968 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:07.969 ThaliTest[2011:3475110] multipeer manager: stop client ti,mer
2016-03-23 11:48:07.969 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:2
2016-03-23 11:48:07.970 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
2016-03-23 11:48:07.971 ThaliTest[2011:,3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:2
2016-03-23 11:48:07.971 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-23 11:48:09.133 ThaliTest[2011:3474885] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:2
,2016-03-23 11:48:10.578 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:10.578 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
,2016-03-23 11:48:10.579 ThaliTest[2011:3475110] multipeer manager: stop client timer
2016-03-23 11:48:10.580 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:48:10.581 ThaliTest[2011:3475110] jxcore: stopListeningForAdve,rtisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:10.584 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50683
,2016-03-23 11:48:27.322 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:27.323 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:27.323 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
ok 106 error should be null
,ok 107 error should be null
,2016-03-23 11:48:27.330 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:27.330 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:27.330 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-23 11:48:29.782 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:29.783 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:29.783 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
,2016-03-23 11:48:29.784 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:29.787 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50685
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-23 11:48:32.033 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:32.033 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:32.034 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:48:32.034 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:32.037 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50687
,2016-03-23 11:48:35.217 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
2016-03-23 11:48:35.218 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:48:35.220 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:48:35.236 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:35.236 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:3
2016-03-23 11:48:35.237 ThaliTest[2011:3475110] THEMultipee,rManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:3
2016-03-23 11:48:35.238 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-23 11:48:35.511 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:35.511 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:35.512 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:35.512 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:35.514 ThaliTest[2011:3475110] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:35.519 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
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
,2016-03-23 11:48:44.294 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
2016-03-23 11:48:44.295 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:48:44.296 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:44.301 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:44.301 ThaliTest[2011:3475110] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:44.303 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-23 11:48:44.550 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:44.552 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:44.555 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:44.555 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:44.556 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-23 11:48:45.188 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
2016-03-23 11:48:45.188 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:48:45.190 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
2016-03-23 11:48:45.193 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:45.195 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-23 11:48:46.176 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:46.177 ThaliTest[2011:3475110] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:46.179 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-23 11:48:46.183 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:46.183 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:46.184 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-23 11:48:47.314 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:47.314 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:4
2016-03-23 11:48:47.315 ThaliTest[2011:3475110] multipeer m,anager: start client restart timer: 0x156ac660
2016-03-23 11:48:47.316 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:4
2016-03-23 11:48:47.316 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-23 11:48:47.319 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:47.320 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
,2016-03-23 11:48:47.320 ThaliTest[2011:3475110] multipeer manager: stop client timer
,2016-03-23 11:48:47.321 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-23 11:48:47.672 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:47.674 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:47.677 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:47.678 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:47.678 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-23 11:48:48.116 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:48.116 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:5
2016-03-23 11:48:48.117 ThaliTest[2011:3475110] multipeer m,anager: start client restart timer: 0x156ac660
2016-03-23 11:48:48.118 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:5
2016-03-23 11:48:48.118 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:48:48.123 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:48.123 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:48.124 ThaliTest[2011:3475110] multipeer manager: stop client ti,mer
2016-03-23 11:48:48.124 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:6
2016-03-23 11:48:48.125 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
2016-03-23 11:48:48.125 ThaliTest[2011:,3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:6
,2016-03-23 11:48:48.125 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-23 11:48:48.335 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:48:48.338 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:48.341 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:48.342 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
,2016-03-23 11:48:48.343 ThaliTest[2011:3475110] multipeer manager: stop client timer
2016-03-23 11:48:48.343 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-23 11:48:48.732 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:48.733 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:48:48.734 ThaliTest[2011:3475110] multipeer m,anager: start client restart timer: 0x156ac660
2016-03-23 11:48:48.734 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
2016-03-23 11:48:48.734 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-23 11:48:48.737 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
,2016-03-23 11:48:48.739 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 152 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:50.849 ThaliTest[2011:3474885] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:48:50.851 ThaliTest[2011:3474885] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:2
ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-23 11:48:52.027 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:48:52.030 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:52.033 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:52.034 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:48:52.035 ThaliTest[2011:3475110] multipeer manager: stop client timer
2016-03-23 11:48:52.035 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-23 11:49:11.824 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:49:11.825 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:49:11.827 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
,2016-03-23 11:49:11.828 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:11.830 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
ok 161 Can call startUpdateAdv,ertisingAndListening without error
2016-03-23 11:49:11.832 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-2,3 11:49:11.834 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-23 11:49:12.398 ThaliTest[2011:3474885] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7","pleaseConnect":0}]
,2016-03-23 11:49:12.401 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:12.403 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:12.404 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:16.395 ThaliTest[2011:3476465] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:16.398 ThaliTest[2011:3476465] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
,2016-03-23 11:49:16.400 ThaliTest[2011:3476465] client session: disconnect
2016-03-23 11:49:16.400 ThaliTest[2011:3476465] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:16.401 ThaliTest[2011:3476465] client sess,ion: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:16.401 ThaliTest[2011:3476465] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: ,Scheduling a connect retry - retries left: 9
,2016-03-23 11:49:16.807 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:49:16.807 ThaliTest[2011:3474885] server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:49:19.413 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:19.414 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:19.414 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:19.754 ThaliTest[2011:3476465] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:19.755 ThaliTest[2011:3476465] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:19.755 ThaliTest[2011:3476465] client session: disconnect
2016-03-23 11:49:19.756 ThaliTest[2011:3476465] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:19.759 ThaliTest[2011:3476465] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:19.759 ThaliTest[2011:3476465] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 11:49:22.770 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:22.771 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:22.772 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:23.554 ThaliTest[2011:3476466] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:23.555 ThaliTest[2011:3476466] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:23.555 ThaliTest[2011:3476466] client session: disconnect
,2016-03-23 11:49:23.555 ThaliTest[2011:3476466] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:23.558 ThaliTest[2011:3476466] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 1,1:49:23.558 ThaliTest[2011:3476466] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 11:49:24.636 ThaliTest[2011:3474885] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:2
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D95DAC2A-FB09-4A72-B9F2-B5180B076,E64:2","pleaseConnect":0}]
,2016-03-23 11:49:25.788 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:49:25.789 ThaliTest[2011:3474885] server session: connect
2016-03-23 11:49:25.789 ThaliTest[2011:3474885] server session: stateChange:0->1 D95DAC2A-FB09-4A72-B9F,2-B5180B076E64:8
,2016-03-23 11:49:25.798 ThaliTest[2011:3474885] server: accepting invitation D95DAC2A-FB09-4A72-B9F2-B5180B076E64
,2016-03-23 11:49:26.589 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:26.590 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:26.591 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:26.772 ThaliTest[2011:3476465] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:26.773 ThaliTest[2011:3476465] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:26.774 ThaliTest[2011:3476465] client session: disconnect
2016-03-23 11:49:26.774 ThaliTest[2011:3476465] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:26.774 ThaliTest[2011:3476465] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
,2016-03-23 11:49:26.774 ThaliTest[2011:3476465] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 11:49:28.862 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:49:28.863 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
,2016-03-23 11:49:28.863 ThaliTest[2011:3474885] server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:49:29.048 ThaliTest[2011:3476558] server session: p2p link connected
,2016-03-23 11:49:29.070 ThaliTest[2011:3474885] server relay: connected (to port: 50694)
,2016-03-23 11:49:29.072 ThaliTest[2011:3474885] server session: stateChange:1->2 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:49:29.782 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:29.783 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:29.783 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:30.998 ThaliTest[2011:3476558] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:30.998 ThaliTest[2011:3476558] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:30.998 ThaliTest[2011:3476558] client session: disconnect
,2016-03-23 11:49:30.999 ThaliTest[2011:3476558] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:49:31.002 ThaliTest[2011:3476558] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:31.002 ThaliTest[2011:3476558] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 11:49:31.829 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:49:31.853 ThaliTest[2011:3474885] client: found updated peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:31.854 ThaliTest[2011:3474885] client: found updated peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier,":"D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8","pleaseConnect":0}]
,2016-03-23 11:49:34.013 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:34.013 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:34.014 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:34.180 ThaliTest[2011:3476558] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:34.180 ThaliTest[2011:3476558] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:34.1,80 ThaliTest[2011:3476558] client session: disconnect
2016-03-23 11:49:34.182 ThaliTest[2011:3476558] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:34.182 ThaliTest[2011:3476558] client session: fireConnectCallb,ack: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:34.183 ThaliTest[2011:3476558] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 11:49:37.188 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:37.189 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:37.189 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:37.331 ThaliTest[2011:3476609] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:37.332 ThaliTest[2011:3476609] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:37.3,33 ThaliTest[2011:3476609] client session: disconnect
2016-03-23 11:49:37.333 ThaliTest[2011:3476609] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:37.334 ThaliTest[2011:3476609] client session: fireConnectCallb,ack: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:37.334 ThaliTest[2011:3476609] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-03-23 11:49:40.343 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:40.344 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:40.344 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:40.509 ThaliTest[2011:3476609] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:40.509 ThaliTest[2011:3476609] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:40.509 ThaliTest[2011:3476609] client session: disconnect
2016-03-23 11:49:40.509 ThaliTest[2011:3476609] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:40.512 ThaliTest[2011:3476609] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:40.512 ThaliTest[2011:3476609] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 11:49:41.841 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:49:41.841 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:49:41.841 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:49:43.523 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:43.524 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:43.524 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:43.770 ThaliTest[2011:3476606] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:43.770 ThaliTest[2011:3476606] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:43.7,71 ThaliTest[2011:3476606] client session: disconnect
2016-03-23 11:49:43.771 ThaliTest[2011:3476606] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:43.774 ThaliTest[2011:3476606] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:43.775 ThaliTest[2011:3476606] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 11:49:46.779 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
2016-03-23 11:49:46.780 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:49:46.780 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:47.230 ThaliTest[2011:3476664] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:47.231 ThaliTest[2011:3476664] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:47.2,31 ThaliTest[2011:3476664] client session: disconnect
,2016-03-23 11:49:47.231 ThaliTest[2011:3476664] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:49:47.235 ThaliTest[2011:3476664] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:49:47.235 ThaliTest[2011:3476664] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 11:49:51.829 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:49:51.856 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:51.858 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:49:55.007 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:49:55.007 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:49:55.007 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:50:07.814 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:50:07.815 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:50:07.815 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:50:11.829 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:50:11.855 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:50:11.855 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:50:20.887 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:50:20.888 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:50:20.888 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:50:31.829 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:50:31.855 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:50:31.858 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:50:33.889 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:50:33.889 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:50:33.890 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:50:46.994 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:50:46.994 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:50:46.995 ThaliTest[2011:3474885] server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:50:51.829 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:50:51.856 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:50:51.858 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:00.269 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:00.269 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:51:00.269 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:51:11.829 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:51:11.858 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:11.858 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:12.746 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:12.747 ThaliTest[2011:3474885] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:51:12.747 ThaliTest[2011:3474885], server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:8 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7)
,2016-03-23 11:51:23.015 ThaliTest[2011:3474885] server relay: socket disconnected
2016-03-23 11:51:23.015 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:51:23.015 ThaliTest[2011:3474885] server relay: 0x155edec0 disconnected, with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"disc,overyActive":false}
2016-03-23 11:51:23.018 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:51:23.020 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:51:23.020 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
,2016-03-23 11:51:23.022 ThaliTest[2011:3475110] server session: disconnect
2016-03-23 11:51:23.022 ThaliTest[2011:3475110] server session: stateChange:2->0 D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:51:23.029 ThaliTest[2011:3475110] multipeer manager: stop client timer
,2016-03-23 11:51:23.029 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 165 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-23 11:51:25.448 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:51:25.450 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:25.453 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
,2016-03-23 11:51:25.466 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:25.467 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,ok 166 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:51:25.471 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 11:51:25.473 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 167 Can call startListeningForAdvertisements without error
,2016-03-23 11:51:26.816 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:26.816 ThaliTest[2011:3474885] server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:27.276 ThaliTest[2011:3474885] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:27.277 ThaliTest[2011:3474885] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:51:27.279 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:27.280 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:27.280 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:28.434 ThaliTest[2011:3477014] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:28.436 ThaliTest[2011:3477014] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:28.4,36 ThaliTest[2011:3477014] client session: disconnect
2016-03-23 11:51:28.437 ThaliTest[2011:3477014] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:28.437 ThaliTest[2011:3477014] client session: fireConnectCallb,ack: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:28.438 ThaliTest[2011:3477014] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-03-23 11:51:30.997 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:30.998 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:30.998 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:31.443 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:31.444 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:31.444 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:32.745 ThaliTest[2011:3477015] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:32.748 ThaliTest[2011:3477015] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:32.748 ThaliTest[2011:3477015] client session: disconnect
2016-03-23 11:51:32.748 ThaliTest[2011:3477015] client session:, stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:32.749 ThaliTest[2011:3477015] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:32.749 ThaliTest[2011:3477015] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 11:51:34.599 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:34.599 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:34.600 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:35.761 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:35.761 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:35.762 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:37.431 ThaliTest[2011:3477018] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:37.431 ThaliTest[2011:3477018] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:37.4,32 ThaliTest[2011:3477018] client session: disconnect
2016-03-23 11:51:37.432 ThaliTest[2011:3477018] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:37.435 ThaliTest[2011:3477018] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:37.435 ThaliTest[2011:3477018] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 11:51:37.802 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:37.803 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:37.803 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:40.443 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:40.443 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:40.444 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:40.943 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:40.943 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:40.944 ThaliTest[2011:3474885] server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:44.064 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:44.065 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:44.065 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:44.528 ThaliTest[2011:3477016] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:44.529 ThaliTest[2011:3477016] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:44.5,30 ThaliTest[2011:3477016] client session: disconnect
2016-03-23 11:51:44.530 ThaliTest[2011:3477016] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:44.531 ThaliTest[2011:3477016] client session: fireConnectCallb,ack: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:44.531 ThaliTest[2011:3477016] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-03-23 11:51:45.465 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:51:45.487 ThaliTest[2011:3474885] client: found updated peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:51:45.493 ThaliTest[2011:3474885] client: found updated peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:47.249 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:47.250 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:47.250 ThaliTest[2011:3474885] server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:47.543 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:47.544 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:47.544 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:49.001 ThaliTest[2011:3477018] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:49.003 ThaliTest[2011:3477018] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:49.004 ThaliTest[2011:3477018] client session: disconnect
2016-03-23 11:51:49.004 ThaliTest[2011:3477018] client session:, stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:51:49.005 ThaliTest[2011:3477018] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:49.005 ThaliTest[2011:3477018] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 11:51:50.466 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:50.466 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:50.466 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:52.011 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:52.012 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:52.013 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:53.604 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:53.604 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:53.605 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:53.715 ThaliTest[2011:3477018] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:51:53.717 ThaliTest[2011:3477018] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:53.7,17 ThaliTest[2011:3477018] client session: disconnect
,2016-03-23 11:51:53.717 ThaliTest[2011:3477018] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:53.720 ThaliTest[2011:3477018] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
,2016-03-23 11:51:53.720 ThaliTest[2011:3477018] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 11:51:56.726 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:56.727 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:51:56.727 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:56.752 ThaliTest[2011:3474885] multipeer session: reset timer
2016-03-23 11:51:56.753 ThaliTest[2011:3474885] server: disconnecting to refresh session (D95DAC2A-FB09-4A72-B9F2-B5180B076E64)
2016-03-23 11:51:56.753 ThaliTest[2011:3474885], server: rejecting invitation from D95DAC2A-FB09-4A72-B9F2-B5180B076E64 due to previous generation (71AA62C9-76E6-4355-A877-ED5FEA587FD9:9 != 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8)
,2016-03-23 11:51:57.772 ThaliTest[2011:3477157] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:51:57.773 ThaliTest[2011:3477157] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:57.773 ThaliTest[2011:3477157] client session: disconnect
,2016-03-23 11:51:57.773 ThaliTest[2011:3477157] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:51:57.776 ThaliTest[2011:3477157] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:51:57.776 ThaliTest[2011:3477157] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 11:52:00.786 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:52:00.787 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:52:00.787 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:01.427 ThaliTest[2011:3477152] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:52:01.428 ThaliTest[2011:3477152] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:52:01.428 ThaliTest[2011:3477152] client session: disconnect
2016-03-23 11:52:01.429 ThaliTest[2011:3477152] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:52:01.429 ThaliTest[2011:3477152] client session: fireConnectCallb,ack: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:52:01.430 ThaliTest[2011:3477152] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 2
,2016-03-23 11:52:04.441 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:52:04.442 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:52:04.442 ThaliTest[2011:3475110] client session: stateChange:0->,1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:05.131 ThaliTest[2011:3477152] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:52:05.132 ThaliTest[2011:3477152] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:52:05.1,33 ThaliTest[2011:3477152] client session: disconnect
2016-03-23 11:52:05.133 ThaliTest[2011:3477152] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:52:05.133 ThaliTest[2011:3477152] client session: fireConnectCallb,ack: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:52:05.134 ThaliTest[2011:3477152] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 1
,2016-03-23 11:52:05.465 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:52:05.485 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:52:05.487 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:08.142 ThaliTest[2011:3475110] jxcore: connect 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:52:08.143 ThaliTest[2011:3475110] client session: connect
2016-03-23 11:52:08.143 ThaliTest[2011:3475110] client session: stateChange:0->1 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:08.796 ThaliTest[2011:3477152] client session: not connected 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:08.797 ThaliTest[2011:3477152] client session: onLinkFailure: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 11:52:08.799 ThaliTest[2011:3477152] client session: disconnect
,2016-03-23 11:52:08.799 ThaliTest[2011:3477152] client session: stateChange:1->0 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
2016-03-23 11:52:08.801 ThaliTest[2011:3477152] client session: fireConnectCallback: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0
2016-03-23 1,1:52:08.802 ThaliTest[2011:3477152] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 11:52:25.465 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:52:25.485 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
2016-03-23 11:52:25.485 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:33.818 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:52:33.820 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:52:33.822 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:33.823 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:33.823 ThaliTest[2011:3475110] multipeer manager: stop client timer
20,16-03-23 11:52:33.824 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-23 11:52:34.605 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:34.606 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:34.607 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:34.610 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-23 11:52:40.949 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:40.950 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:40.951 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:40.954 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-23 11:52:41.422 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:41.423 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:41.423 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:41.426 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50737
,2016-03-23 11:52:41.600 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:41.602 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-23 11:52:41.606 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:41.608 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-23 11:52:41.729 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:41.729 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:41.730 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 11:52:41.731 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:52:41.732 ThaliTest[2011,:3475110] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:41.984 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:41.985 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:41.986 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:41.989 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50739
,2016-03-23 11:52:42.183 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
2016-03-23 11:52:42.184 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:42.187 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,ok 175 no errors
,2016-03-23 11:52:42.191 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:52:42.195 ThaliTest[2011:34751,10] jxcore: startListeningForAdvertisements: success
ok 176 still no errors
# teardown
,2016-03-23 11:52:42.360 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:42.361 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:42.361 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:42.362 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:52:42.362 ThaliTest[2011:3475110] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:52:42.366 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:42.504 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:42.505 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:42.506 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:42.510 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50741
,2016-03-23 11:52:42.649 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:52:42.649 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:10
2016-03-23 11:52:42.650 ThaliTest[2011:3475110] multipeer ,manager: start client restart timer: 0x156ac660
2016-03-23 11:52:42.651 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:10
2016-03-23 11:52:42.651 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,ok 177 no errors
,2016-03-23 11:52:42.655 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:52:42.656 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:42.656 ThaliTest[2011:3475110] multipeer manager: stop client timer
2016-03-23 11:52:42.657 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:11
2016-03-23 11:52:42.657 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
2016-03-23 11:52:42.658 ThaliTest[2011,:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:11
2016-03-23 11:52:42.658 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
,# teardown
,2016-03-23 11:52:42.947 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:42.948 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:42.948 ThaliTest[2011:3475110] multipeer manager: stop client timer
20,16-03-23 11:52:42.949 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:42.949 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:42.959 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:43.112 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:43.113 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:43.114 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:43.118 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50745
,2016-03-23 11:52:43.597 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:43.598 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:43.598 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
ok 179 no errors
,2016-03-23 11:52:43.601 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:43.602 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:43.602 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
ok 180 still no errors
,# teardown
,2016-03-23 11:52:46.780 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:46.781 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:46.781 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:46.782 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:46.785 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:47.907 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:47.908 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:47.909 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:47.912 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. can get the network status before starting
,ok 181 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-23 11:52:48.607 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:48.609 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:48.611 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:48.615 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 182 specific error expected
,# teardown
,# setup
,2016-03-23 11:52:48.968 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:48.970 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:48.971 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:48.974 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50747
,2016-03-23 11:52:49.247 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
,2016-03-23 11:52:49.249 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:49.260 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:52:49.263 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:52:49.264 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:12
,2016-03-23 11:52:49.266 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:12
,2016-03-23 11:52:49.269 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 183 connection to servers manager should succeed after starting
,ok 184 connection to router server should succeed after starting
,2016-03-23 11:52:49.323 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:49.324 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:49.324 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 11:52:49.325 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:52:49.325 ThaliTest[2011:3475110] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:52:49.330 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
DEBUG createNativeListener: mux close
,ok 185 is stopped after calling stop
DEBUG createNativeListener: incoming socket close
,ok 186 connection to servers manager should fail after stopping
,ok 187 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-23 11:52:49.691 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:49.692 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:49.693 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:49.695 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. make sure terminateConnection is properly hooked up
,ok 188 called with right arguments
,# teardown
,# setup
,2016-03-23 11:52:50.295 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:50.295 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:50.296 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:50.299 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. make sure terminateListener is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-23 11:52:54.873 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:54.874 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:54.875 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:54.878 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure we actually call kill connections properly
,2016-03-23 11:52:56.788 ThaliTest[2011:3475110] jxcore: killConnections
2016-03-23 11:52:56.789 ThaliTest[2011:3475110] jxcore: killConnections: badParam
,not ok 190 should not fail on iOS
  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-23 11:52:57.246 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 11:52:57.247 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 11:52:57.248 ThaliTest[2011:3,475110] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:57.251 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50754
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":50753,"error":{}}
,2016-03-23 11:52:57.355 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:57.356 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
,2016-03-23 11:52:57.357 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:57.360 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:57.363 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,ok 191 failure reason is as expected
,ok 192 error description is as expected
,ok 193 must be stopped
,# teardown
,# setup
,2016-03-23 11:52:57.766 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:57.768 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:57.770 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:57.774 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50756
,ok 194 peerIdentifier matches
,ok 195 error description matches
,# teardown
,2016-03-23 11:52:58.153 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:58.154 ThaliTest[2011:3475110] THEMultipeerManager stopping peer
2016-03-23 11:52:58.154 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:58.155 ThaliTest[2011:3475110] jxcore: stopListeningForAdverti,sements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:58.157 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:58.261 ThaliTest[2011:3475110] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:58.264 ThaliTest[2011:3475110] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:58.265 ThaliTest[2011:3475110] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:58.270 ThaliTest[2011:3475110] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50758
,2016-03-23 11:52:58.431 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements
2016-03-23 11:52:58.431 ThaliTest[2011:3475110] multipeer manager: start client restart timer: 0x156ac660
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 196 discoveryActive matches
ok 197 advertisingActive matches
,2016-03-23 11:52:58.441 ThaliTest[2011:3475110] jxcore: startListeningForAdvertisements: success
2016-03-23 11:52:58.443 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:58.443 ThaliTest[2011:3475110] THEMultipeerManager stopp,ing peer
2016-03-23 11:52:58.443 ThaliTest[2011:3475110] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:58.446 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements
2016-03-23 11:52:58.447 ThaliTest[2011:3475110] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 198 discoveryActive matches
,ok 199 advertisingActive matches
2016-03-23 11:52:58.453 ThaliTest[2011:3475110] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50760
,2016-03-23 11:52:58.467 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:52:58.468 ThaliTest[2011:3475110] server: starting 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:52:58.468 ThaliTest[2011:3475110] multipeer ,manager: start client restart timer: 0x156ac660
,2016-03-23 11:52:58.471 ThaliTest[2011:3475110] THEMultipeerManager initialized peer 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:52:58.471 ThaliTest[2011:3475110] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-23 11:52:59.583 ThaliTest[2011:3474885] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:59.593 ThaliTest[2011:3474885] client: found new peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:53:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:53:18.496 ThaliTest[2011:3474885] client: found updated peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:53:18.497 ThaliTest[2011:3474885] client: found updated peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:53:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:53:38.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:53:38.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:53:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:53:58.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:53:58.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:54:18.471 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:54:18.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:54:18.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:54:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:54:38.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:54:38.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:54:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:54:58.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:54:58.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:55:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:55:18.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:55:18.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:55:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:55:38.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:55:38.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:55:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:55:58.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:55:58.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:56:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:56:18.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:56:18.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:56:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:56:38.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:56:38.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:56:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:56:58.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:56:58.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:57:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:57:18.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:57:18.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:57:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:57:38.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:57:38.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:57:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:57:58.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:57:58.497 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:58:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:58:18.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:58:18.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:58:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:58:38.493 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:58:38.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:58:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:58:58.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:58:58.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:59:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:59:18.492 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:59:18.500 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:59:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:59:38.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:59:38.497 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:59:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 11:59:58.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:59:58.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:00:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:00:18.497 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:00:18.499 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:00:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:00:38.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:00:38.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:00:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:00:58.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:00:58.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:01:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:01:18.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:01:18.497 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:01:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:01:38.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:01:38.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:01:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:01:58.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:01:58.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:02:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:02:18.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:02:18.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:02:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:02:38.493 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:02:38.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:02:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:02:58.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:02:58.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:03:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:03:18.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:03:18.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:03:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:03:38.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:03:38.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:03:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:03:58.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:03:58.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:04:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:04:18.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:04:18.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:04:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:04:38.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:04:38.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:04:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:04:58.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:04:58.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:05:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:05:18.493 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:05:18.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 12:05:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:05:38.495 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:05:38.496 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:05:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:05:58.493 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:05:58.495 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:06:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:06:18.497 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:06:18.497 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:06:38.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:06:38.494 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:06:38.494 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:06:58.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:06:58.496 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:06:58.498 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:07:18.472 ThaliTest[2011:3474885] multipeer manager: restart client
,2016-03-23 12:07:18.492 ThaliTest[2011:3474885] client: found existing peer: D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 12:07:18.497 ThaliTest[2011:3474885] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13

```
