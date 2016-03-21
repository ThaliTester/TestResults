#### Test 62548124bd1cdb6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F33E619D-6C91-45C8-BB0C-C86DEAE9041F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F33E619D-6C91-45C8-BB0C-C86DEAE9041F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53524"
,(lldb)     command script import "/tmp/F33E619D-6C91-45C8-BB0C-C86DEAE9041F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 07:31:41.097 ThaliTest[1846:3149417] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A6CC8CCC-7B37-4426-85AD-0A2F3FEF324A/Library/Cookies/Cookies.binarycookies
,2016-03-21 07:31:41.520 ThaliTest[1846:3149417] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 07:31:41.522 ThaliTest[1846:3149417] Multi-tasking -> Device: YES, App: YES
,2016-03-21 07:31:41.542 ThaliTest[1846:3149417] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 07:31:43.395 ThaliTest[1846:3149417] Using UIWebView
,2016-03-21 07:31:43.404 ThaliTest[1846:3149417] [CDVTimer][handleopenurl] 0.384986ms
,2016-03-21 07:31:43.412 ThaliTest[1846:3149417] [CDVTimer][intentandnavigationfilter] 7.220984ms
2016-03-21 07:31:43.413 ThaliTest[1846:3149417] [CDVTimer][gesturehandler] 0.365973ms
2016-03-21 07:31:43.413 ThaliTest[1846:3149417] [CDVTimer][TotalPluginS,tartup] 9.574056ms
,2016-03-21 07:31:49.952 ThaliTest[1846:3149417] Resetting plugins due to page load.
,2016-03-21 07:31:52.917 ThaliTest[1846:3149417] Finished load of: file:///var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/index.html
,2016-03-21 07:31:53.139 ThaliTest[1846:3149417] JXcore Cordova plugin initializing
2016-03-21 07:31:53.140 ThaliTest[1846:3149611] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 07:32:00.365 ThaliTest[1846:3149611] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 07:32:00.365 ThaliTest[1846:3149611] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 07:32:00.366 ThaliTest[1846:3149611] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:32:00.367 ThaliTest[1846:3149611] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8F73A2C3-2B41-42A7-9F9D-8C64FA47E6B1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 07:32:06.205 ThaliTest[1846:3149417] THREAD WARNING: ['JXcore'] took '5524.670166' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65164
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65166
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
,DEBUG createNativeListener: listening 65169
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
,DEBUG createNativeListener: listening 65174
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
,DEBUG createNativeListener: listening 65179
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
,DEBUG createNativeListener: listening 65183
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
,DEBUG createNativeListener: listening 65187
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
,DEBUG createNativeListener: listening 65191
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
,DEBUG createNativeListener: listening 65195
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
,DEBUG createNativeListener: listening 65247
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
,DEBUG createNativeListener: listening 65251
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
,DEBUG createNativeListener: listening 65263
,2016-03-21 07:36:13.888 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:13.891 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 07:36:13.897 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:13.900 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 07:36:14.054 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:14.055 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
,2016-03-21 07:36:14.055 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:14.057 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:14.060 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65265
,2016-03-21 07:36:14.345 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
,2016-03-21 07:36:14.348 ThaliTest[1846:3149611] multipeer manager: start client restart timer: 0x17536850
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:36:14.351 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-21 07:36:14.370 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:36:14.373 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 07:36:14.610 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:14.611 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:14.611 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 07:36:14.612 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,2016-03-21 07:36:14.613 ThaliTest[1846:3149611] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 07:36:14.617 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65267
,2016-03-21 07:36:14.852 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:14.853 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:1
2016-03-21 07:36:14.854 ThaliTest[1846:3149611] multipeer m,anager: start client restart timer: 0x17536850
2016-03-21 07:36:14.855 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:1
2016-03-21 07:36:14.855 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-21 07:36:14.874 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:14.875 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:14.876 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:36:14.876 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:2
2016-03-21 07:36:14.877 ThaliTest[1846:3149611] multipeer manager: start client restart timer: 0x17536850
2016-03-21 07:36:14.878 ThaliTest[1846:,3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:2
2016-03-21 07:36:14.878 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-21 07:36:15.286 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:15.286 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:15.287 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:36:15.287 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:15.290 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 07:36:15.292 ThaliTest[1846:31496,11] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65272
,2016-03-21 07:36:16.208 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:16.209 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:16.209 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-21 07:36:16.215 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:16.216 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:16.216 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-21 07:36:17.818 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:17.819 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:17.819 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
2016-03-21 07:36:17.820 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:17.823 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65274
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 07:36:20.599 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:20.600 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:20.600 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 07:36:20.601 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:20.603 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65276
,2016-03-21 07:36:20.777 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
2016-03-21 07:36:20.778 ThaliTest[1846:3149611] multipeer manager: start client restart timer: 0x17536850
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:36:20.780 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
,2016-03-21 07:36:20.795 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:20.796 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:3
2016-03-21 07:36:20.797 ThaliTest[1846:3149611] THEMultipee,rManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:3
2016-03-21 07:36:20.797 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-21 07:36:21.099 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:21.099 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:21.100 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:21.102 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
2016-03-21 07:36:21.103 ThaliTest[1846:3149611] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-21 07:36:21.105 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
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
,2016-03-21 07:36:26.460 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
2016-03-21 07:36:26.461 ThaliTest[1846:3149611] multipeer manager: start client restart timer: 0x17536850
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:36:26.462 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:26.466 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
2016-03-21 07:36:26.466 ThaliTest[1846:3149611] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:26.474 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 07:36:26.744 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:26.746 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:26.749 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:26.750 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:26.750 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 07:36:27.237 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
2016-03-21 07:36:27.238 ThaliTest[1846:3149611] multipeer manager: start client restart timer: 0x17536850
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:36:27.240 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
ok 133 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:27.243 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:36:27.245 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 07:36:27.309 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
2016-03-21 07:36:27.310 ThaliTest[1846:3149611] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:27.312 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-21 07:36:27.317 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:27.317 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:3,6:27.317 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 07:36:27.842 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:27.843 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:4
2016-03-21 07:36:27.843 ThaliTest[1846:3149611] multipeer m,anager: start client restart timer: 0x17536850
2016-03-21 07:36:27.844 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:4
2016-03-21 07:36:27.844 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-21 07:36:27.846 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:27.847 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016,-03-21 07:36:27.847 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:36:27.848 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-21 07:36:27.965 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:27.967 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:27.970 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:27.970 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:27.970 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: suc,cess
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 07:36:28.890 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:28.890 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:5
2016-03-21 07:36:28.891 ThaliTest[1846:3149611] multipeer m,anager: start client restart timer: 0x17536850
2016-03-21 07:36:28.892 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:5
2016-03-21 07:36:28.892 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-21 07:36:28.894 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:28.895 ThaliTest[1846:3149611] THEMultipeerManager stopping pee,r
2016-03-21 07:36:28.895 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:36:28.896 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:6
2016-03-21 07:36:28.896 ThaliTest[1846:3149611] multipeer mana,ger: start client restart timer: 0x17536850
,2016-03-21 07:36:28.902 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:6
2016-03-21 07:36:28.904 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdv,ertisingAndListening twice without error
# setup
,2016-03-21 07:36:28.970 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:36:28.972 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:28.976 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:28.976 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:28.976 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:36:28.977 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 07:36:29.352 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:29.353 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:29.353 ThaliTest[1846:3149611] multipeer m,anager: start client restart timer: 0x17536850
2016-03-21 07:36:29.354 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:29.354 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-21 07:36:29.356 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-21 07:36:29.358 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:30.622 ThaliTest[1846:3149417] client: found new peer: B601A2E8-785A-495E-A366-56984BFF195E:7
ok 147 peers must be an array
ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 07:36:31.433 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:36:31.435 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:31.437 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:31.438 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:36:31.439 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:36:31.439 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 07:36:31.609 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:36:31.610 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:36:31.610 ThaliTest[1846:3149611] multipeer m,anager: start client restart timer: 0x17536850
2016-03-21 07:36:31.611 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:36:31.611 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-21 07:36:31.616 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"dis,coveryActive":true}
,2016-03-21 07:36:31.618 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:32.552 ThaliTest[1846:3149417] client: found new peer: B601A2E8-785A-495E-A366-56984BFF195E:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B601A2E8-785A-495E-A366-56984BFF195E:7","pleaseConnect":0}]
,2016-03-21 07:36:32.557 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:36:32.558 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:36:32.558 ThaliTest[1846:3149611] client session: reverseConnect
2016-03-21 07:36:32.558 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:7
,2016-03-21 07:36:32.678 ThaliTest[1846:3149417] client: lost peer: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:36:32.678 ThaliTest[1846:3149417] client session: onPeerLost: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:36:32.679 ThaliTest[184,6:3149417] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:36:32.679 ThaliTest[1846:3149417] client session: disconnect
2016-03-21 07:36:32.679 ThaliTest[1846:3149417] client session: stateChange:1->0 B601A2E8-785A-495E-,A366-56984BFF195E:7
2016-03-21 07:36:32.680 ThaliTest[1846:3149417] client session: no connect callback (server initiated)
,2016-03-21 07:36:33.760 ThaliTest[1846:3149417] client: found updated peer: B601A2E8-785A-495E-A366-56984BFF195E:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B601A2E8-785A-495E-A366-56984BFF195E:8","pleaseConnect":0}]
,2016-03-21 07:36:33.782 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:33.783 ThaliTest[1846:3149417] server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:35.807 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:35.809 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:35.809 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:39.421 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:39.422 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:39.422 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:42.559 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 07:36:43.360 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:43.362 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:43.362 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:45.566 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:36:45.566 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:36:45.567 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:36:45.567 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:36:45.803 ThaliTest[1846:3150082] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:36:45.803 ThaliTest[1846:3150082] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:36:45.804 ThaliTest[1846:3150082] client session: disconnect
,2016-03-21 07:36:45.804 ThaliTest[1846:3150082] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:36:45.807 ThaliTest[1846:3150082] client session: no connect callback (server initiated)
,2016-03-21 07:36:46.485 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:46.485 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:46.486 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:49.572 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:49.573 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:49.573 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:51.612 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:36:51.629 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:36:52.761 ThaliTest[1846:3149417] multipeer session: reset timer
,2016-03-21 07:36:52.761 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:52.761 ThaliTest[1846:3149417] server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:55.568 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 07:36:55.967 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:55.968 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:55.968 ThaliTest[1846:3149417] server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:36:58.583 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:36:58.583 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:36:58.584 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:36:58.584 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:36:58.912 ThaliTest[1846:3150082] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:36:58.914 ThaliTest[1846:3150082] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:36:58.9,14 ThaliTest[1846:3150082] client session: disconnect
2016-03-21 07:36:58.915 ThaliTest[1846:3150082] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:36:58.915 ThaliTest[1846:3150082] client session: no connect callb,ack (server initiated)
,2016-03-21 07:36:59.078 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:36:59.079 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:36:59.079 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:37:02.202 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:37:02.203 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:37:02.203 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7)
,2016-03-21 07:37:08.585 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 07:37:11.601 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:37:11.602 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:37:11.603 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:37:11.603 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:11.612 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:37:11.623 ThaliTest[1846:3149417] client: lost peer: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:37:11.624 ThaliTest[1846:3149417] client session: onPeerLost: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:37:11.624 ThaliTest[184,6:3149417] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:37:11.624 ThaliTest[1846:3149417] client session: disconnect
2016-03-21 07:37:11.625 ThaliTest[1846:3149417] client session: stateChange:1->0 B601A2E8-785A-495E-,A366-56984BFF195E:8
2016-03-21 07:37:11.625 ThaliTest[1846:3149417] client session: no connect callback (server initiated)
,2016-03-21 07:37:11.637 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B601A2E8-785A-495E-A366-56984BFF195E:8","pleaseConnect":0}]
,2016-03-21 07:37:21.604 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 07:37:24.610 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:37:24.611 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:37:24.611 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:37:24.612 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:24.879 ThaliTest[1846:3150049] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:37:24.880 ThaliTest[1846:3150049] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:37:24.8,80 ThaliTest[1846:3150049] client session: disconnect
2016-03-21 07:37:24.881 ThaliTest[1846:3150049] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:24.884 ThaliTest[1846:3150049] client session: no connect callback (server initiated)
,2016-03-21 07:37:31.612 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:37:31.630 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:34.613 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 07:37:37.625 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:37:37.625 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:37:37.626 ThaliTest[1846:3149611] client session: reverseConnect
2016-03-21 07:37:37.626 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:37.925 ThaliTest[1846:3150301] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:37:37.927 ThaliTest[1846:3150301] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:37:37.9,27 ThaliTest[1846:3150301] client session: disconnect
2016-03-21 07:37:37.927 ThaliTest[1846:3150301] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:37:37.928 ThaliTest[1846:3150301] client session: no connect callb,ack (server initiated)
,2016-03-21 07:37:47.627 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 07:37:50.632 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:37:50.632 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:37:50.633 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:37:50.633 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:50.959 ThaliTest[1846:3150301] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:50.961 ThaliTest[1846:3150301] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:37:50.961 ThaliTest[1846:3150301] client session: disconnect
2016-03-21 07:37:50.962 ThaliTest[1846:3150301] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:37:50.964 ThaliTest[1846:3150301] client session: no connect callback (server initiated)
,2016-03-21 07:37:51.612 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:37:51.629 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:00.634 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 07:38:03.650 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:38:03.651 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:38:03.652 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:38:03.652 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:04.026 ThaliTest[1846:3150369] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:04.028 ThaliTest[1846:3150369] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:38:04.0,28 ThaliTest[1846:3150369] client session: disconnect
2016-03-21 07:38:04.028 ThaliTest[1846:3150369] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:04.030 ThaliTest[1846:3150369] client session: no connect callback (server initiated)
,2016-03-21 07:38:11.612 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:38:11.627 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:13.653 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 07:38:16.666 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:38:16.666 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:38:16.667 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:38:16.667 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:17.176 ThaliTest[1846:3150486] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:17.177 ThaliTest[1846:3150486] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
,2016-03-21 07:38:17.178 ThaliTest[1846:3150486] client session: disconnect
2016-03-21 07:38:17.179 ThaliTest[1846:3150486] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:17.179 ThaliTest[1846:3150486] client session: no connect callback (server initiated)
,2016-03-21 07:38:26.668 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 07:38:29.683 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:38:29.684 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:38:29.685 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:38:29.685 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:29.861 ThaliTest[1846:3150509] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:29.861 ThaliTest[1846:3150509] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:38:29.8,61 ThaliTest[1846:3150509] client session: disconnect
2016-03-21 07:38:29.861 ThaliTest[1846:3150509] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:29.862 ThaliTest[1846:3150509] client session: no connect callback (server initiated)
,2016-03-21 07:38:31.611 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:38:31.625 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:39.686 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 07:38:39.821 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:38:39.824 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:38:39.826 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:38:39.827 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:38:39.827 ThaliTest[1846:3149611] multipeer manager: stop client timer
20,16-03-21 07:38:39.828 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-21 07:38:40.050 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndListening
2016-03-21 07:38:40.050 ThaliTest[1846:3149611] server: starting 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
2016-03-21 07:38:40.051 ThaliTest[1846:3149611] multipeer m,anager: start client restart timer: 0x17536850
2016-03-21 07:38:40.051 ThaliTest[1846:3149611] THEMultipeerManager initialized peer 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
2016-03-21 07:38:40.051 ThaliTest[1846:3149611] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
2016-03-21 07:38:40.053 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-21 07:38:40.054 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success
ok 161 Can call startListeningForAdvertisements without error
,2016-03-21 07:38:40.961 ThaliTest[1846:3149417] client: found new peer: B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:40.963 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:40.963 ThaliTest[1846:3,149611] client: server will connect
2016-03-21 07:38:40.964 ThaliTest[1846:3149611] client session: reverseConnect
2016-03-21 07:38:40.964 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:41.738 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:38:41.738 ThaliTest[1846:3149417] server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:38:42.144 ThaliTest[1846:3150607] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:42.144 ThaliTest[1846:3150607] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:38:42.145 ThaliTest[1846:3150607] client session: disconnect
,2016-03-21 07:38:42.145 ThaliTest[1846:3150607] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:42.148 ThaliTest[1846:3150607] client session: no connect callback (server initiated)
,2016-03-21 07:38:45.370 ThaliTest[1846:3149417] multipeer session: reset timer
,2016-03-21 07:38:45.370 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
,2016-03-21 07:38:45.370 ThaliTest[1846:3149417] server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:38:48.458 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:38:48.459 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:38:48.459 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:38:50.911 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 07:38:51.645 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:38:51.645 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:38:51.646 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:38:53.925 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:53.926 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:38:53.926 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:38:53.926 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:38:54.269 ThaliTest[1846:3150649] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:54.269 ThaliTest[1846:3150649] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:38:54.269 ThaliTest[1846:3150649] client session: disconnect
,2016-03-21 07:38:54.269 ThaliTest[1846:3150649] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:38:54.273 ThaliTest[1846:3150649] client session: no connect callback (server initiated)
,2016-03-21 07:38:54.734 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:38:54.734 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:38:54.735 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:38:57.931 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:38:57.931 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:38:57.931 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:38:59.998 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:39:00.028 ThaliTest[1846:3149417] client: found updated peer: B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:39:01.065 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:39:01.066 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:39:01.066 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:39:03.927 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 07:39:04.214 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:39:04.215 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:39:04.215 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:39:06.939 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:06.940 ThaliTest[1846:3149611] client: server will connect
2016-03-21 07:39:06.940 ThaliTest[1846:3149611] client session: reverseConn,ect
2016-03-21 07:39:06.941 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:39:07.373 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:39:07.373 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:39:07.373 ThaliTest[1846:3149417] server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:39:07.767 ThaliTest[1846:3150649] client session: not connected B601A2E8-785A-495E-A366-56984BFF195E:9
2016-03-21 07:39:07.768 ThaliTest[1846:3150649] client session: onLinkFailure: B601A2E8-785A-495E-A366-56984BFF195E
2016-03-21 07:39:07.7,68 ThaliTest[1846:3150649] client session: disconnect
2016-03-21 07:39:07.768 ThaliTest[1846:3150649] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:39:07.771 ThaliTest[1846:3150649] client session: no connect callback (server initiated)
,2016-03-21 07:39:10.584 ThaliTest[1846:3149417] multipeer session: reset timer
2016-03-21 07:39:10.584 ThaliTest[1846:3149417] server: disconnecting to refresh session (B601A2E8-785A-495E-A366-56984BFF195E)
2016-03-21 07:39:10.585 ThaliTest[1846:3149417], server: rejecting invitation from B601A2E8-785A-495E-A366-56984BFF195E due to previous generation (9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9 != 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8)
,2016-03-21 07:39:16.942 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 07:39:19.946 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:39:19.947 ThaliTest[1846:3149611] client: server will connect
,2016-03-21 07:39:19.948 ThaliTest[1846:3149611] client session: reverseConnect
2016-03-21 07:39:19.948 ThaliTest[1846:3149611] client session: stateChange:0->1 B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:39:19.998 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:39:20.021 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:39:29.948 ThaliTest[1846:3149417] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 07:39:32.959 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:32.960 ThaliTest[1846:3149611] client: already connect(ing/ed) to B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:32.960 Thali,Test[1846:3149611] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 07:39:35.971 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:35.971 ThaliTest[1846:3149611] client: already connect(ing/ed) to B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:35.972 Thali,Test[1846:3149611] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 07:39:38.984 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:38.985 ThaliTest[1846:3149611] client: already connect(ing/ed) to B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:38.985 Thali,Test[1846:3149611] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 07:39:39.998 ThaliTest[1846:3149417] multipeer manager: restart client
,2016-03-21 07:39:40.017 ThaliTest[1846:3149417] client: found existing peer: B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:39:41.997 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:41.998 ThaliTest[1846:3149611] client: already connect(ing/ed) to B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:41.998 Thali,Test[1846:3149611] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 07:39:45.019 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:45.019 ThaliTest[1846:3149611] client: already connect(ing/ed) to B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:45.020 Thali,Test[1846:3149611] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 07:39:48.038 ThaliTest[1846:3149611] jxcore: connect B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:48.039 ThaliTest[1846:3149611] client: already connect(ing/ed) to B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:39:48.039 Thali,Test[1846:3149611] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 07:39:48.122 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:39:48.124 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:39:48.127 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
2016-03-21 07:39:48.127 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:39:48.128 ThaliTest[1846:3149611] client session: disconnect
2016-03-21 0,7:39:48.128 ThaliTest[1846:3149611] client session: stateChange:1->0 B601A2E8-785A-495E-A366-56984BFF195E:9
2016-03-21 07:39:48.129 ThaliTest[1846:3149611] multipeer manager: stop client timer
2016-03-21 07:39:48.129 ThaliTest[1846:3149611] jxcore: stopA,dvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-21 07:39:48.429 ThaliTest[1846:3149611] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:39:48.431 ThaliTest[1846:3149611] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 07:39:48.433 ThaliTest[1846:3149611] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:48.437 ThaliTest[1846:3149611] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-21 07:39:48.688 ThaliTest[1846:3149611] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 07:39:48.689 ThaliTest[1846:3149611] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 07:39:48.690 ThaliTest[1846:3,149611] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:48.693 ThaliTest[1846:3149611] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-21 07:39:48.987 ThaliTest[1846:3149611] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 07:39:48.988 ThaliTest[1846:3149611] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 07:39:48.989 ThaliTest[1846:3,149611] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:48.992 ThaliTest[1846:3149611] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65311
,2016-03-21 07:39:49.127 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:39:49.129 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-21 07:39:49.132 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:39:49.135 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-21 07:39:49.251 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening
,2016-03-21 07:39:49.252 ThaliTest[1846:3149611] THEMultipeerManager stopping peer
2016-03-21 07:39:49.253 ThaliTest[1846:3149611] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:39:49.255 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:39:49.258 ThaliTest[1846:3149611] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-21 07:39:49.499 ThaliTest[1846:3149611] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:39:49.501 ThaliTest[1846:3149611] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 07:39:49.503 ThaliTest[1846:3149611] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:49.507 ThaliTest[1846:3149611] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65313
,2016-03-21 07:39:49.609 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements
,2016-03-21 07:39:49.611 ThaliTest[1846:3149611] multipeer manager: start client restart timer: 0x17536850
,2016-03-21 07:39:49.622 ThaliTest[1846:3149417] client: found new peer: B601A2E8-785A-495E-A366-56984BFF195E:9
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:39:49.6,24 ThaliTest[1846:3149611] jxcore: startListeningForAdvertisements: success

```
