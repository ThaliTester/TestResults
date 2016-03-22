#### Test 63680118d4cb974_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AABB90DE-E77E-4577-ADC5-552E287EC111/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AABB90DE-E77E-4577-ADC5-552E287EC111/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54798"
,(lldb)     command script import "/tmp/AABB90DE-E77E-4577-ADC5-552E287EC111/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 14:36:36.744 ThaliTest[1961:3347224] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/818FF039-CC18-4A13-880A-0F3B8AE778B6/Library/Cookies/Cookies.binarycookies
,2016-03-22 14:36:37.124 ThaliTest[1961:3347224] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 14:36:37.125 ThaliTest[1961:3347224] Multi-tasking -> Device: YES, App: YES
,2016-03-22 14:36:37.150 ThaliTest[1961:3347224] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 14:36:39.138 ThaliTest[1961:3347224] Using UIWebView
,2016-03-22 14:36:39.145 ThaliTest[1961:3347224] [CDVTimer][handleopenurl] 0.420988ms
,2016-03-22 14:36:39.153 ThaliTest[1961:3347224] [CDVTimer][intentandnavigationfilter] 7.315040ms
2016-03-22 14:36:39.153 ThaliTest[1961:3347224] [CDVTimer][gesturehandler] 0.326991ms
2016-03-22 14:36:39.154 ThaliTest[1961:3347224] [CDVTimer][TotalPluginStartup] 9.653986ms
,2016-03-22 14:36:46.538 ThaliTest[1961:3347224] Resetting plugins due to page load.
,2016-03-22 14:36:49.611 ThaliTest[1961:3347224] Finished load of: file:///var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/index.html
,2016-03-22 14:36:49.851 ThaliTest[1961:3347224] JXcore Cordova plugin initializing
,2016-03-22 14:36:49.853 ThaliTest[1961:3347461] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 14:36:57.134 ThaliTest[1961:3347461] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:36:57.134 ThaliTest[1961:3347461] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:36:57.134 ThaliTest[1961:3347461] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:36:57.136 ThaliTest[1961:3347461] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/26EB29D5-4DC9-4FF3-B6C0-D0C34DE434B7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 14:37:03.005 ThaliTest[1961:3347224] THREAD WARNING: ['JXcore'] took '5555.690186' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50279
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50281
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
,DEBUG createNativeListener: listening 50284
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
,DEBUG createNativeListener: listening 50288
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
,DEBUG createNativeListener: listening 50293
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
,DEBUG createNativeListener: listening 50297
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
,DEBUG createNativeListener: listening 50301
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
,DEBUG createNativeListener: listening 50305
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
,DEBUG createNativeListener: listening 50309
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
,DEBUG createNativeListener: listening 50361
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
,DEBUG createNativeListener: listening 50365
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
,DEBUG createNativeListener: listening 50377
,2016-03-22 14:39:15.091 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.094 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-22 14:39:15.100 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.103 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-22 14:39:15.310 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:15.311 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:15.311 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: suc,cess
,2016-03-22 14:39:15.313 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.315 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50379
,2016-03-22 14:39:15.691 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
,2016-03-22 14:39:15.694 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:15.696 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-22 14:39:15.713 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:15.715 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-22 14:39:16.006 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:16.006 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:16.007 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 14:39:16.007 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:16.008 ThaliTest[1961:3347461] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:16.012 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50381
,2016-03-22 14:39:16.595 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:39:16.597 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:1
,2016-03-22 14:39:16.598 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
2016-03-22 14:39:16.599 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:1
2016-03-22 14:39:16.599 ,ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-22 14:39:16.616 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:16.617 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:16.617 ThaliTest[1961:3347461] multipeer manager: stop client timer
,2016-03-22 14:39:16.620 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:2
2016-03-22 14:39:16.623 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
2016-03-22 14:39:16.623 ThaliTest[1961:33474,61] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:2
2016-03-22 14:39:16.623 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-22 14:39:17.173 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:17.174 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
,2016-03-22 14:39:17.176 ThaliTest[1961:3347461] multipeer manager: stop client timer
2016-03-22 14:39:17.176 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:17.180 ThaliTest[1961:3347461] jxcore: stopListeningForAdve,rtisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:17.182 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50386
,2016-03-22 14:39:18.743 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:18.744 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:18.744 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,2016-03-22 14:39:18.751 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:18.752 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:18.752 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-22 14:39:19.035 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:19.036 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:19.036 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:19.037 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:19.040 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50388
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-22 14:39:19.661 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:19.662 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:19.662 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:19.663 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:19.666 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50390
,2016-03-22 14:39:20.091 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
2016-03-22 14:39:20.091 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:20.095 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,2016-03-22 14:39:20.117 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:20.117 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:3
2016-03-22 14:39:20.118 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:3
2016-03-22 14:39:20.118 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-22 14:39:20.318 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:20.319 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:20.319 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:20.320 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,2016-03-22 14:39:20.322 ThaliTest[1961:3347461] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:20.326 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
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
,2016-03-22 14:39:25.694 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
2016-03-22 14:39:25.694 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 14:39:25.696 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-22 14:39:25.700 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:25.701 ThaliTest[1961:3347461] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:25.709 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-22 14:39:26.038 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:26.040 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:26.043 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:26.044 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:26.045 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-22 14:39:26.571 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
2016-03-22 14:39:26.572 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:26.575 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
2016-03-22 14:39:26.579 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"disco,veryActive":true}
2016-03-22 14:39:26.581 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-22 14:39:26.707 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
2016-03-22 14:39:26.708 ThaliTest[1961:3347461] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:26.711 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-22 14:39:26.714 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2,016-03-22 14:39:26.715 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:26.715 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-22 14:39:30.663 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:30.664 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:4
2016-03-22 14:39:30.665 ThaliTest[1961:3347461] multipeer m,anager: start client restart timer: 0x1755d560
2016-03-22 14:39:30.665 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:4
2016-03-22 14:39:30.665 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-22 14:39:30.668 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:30.668 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
,2016-03-22 14:39:30.668 ThaliTest[1961:3347461] multipeer manager: stop client timer
2016-03-22 14:39:30.671 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-22 14:39:31.011 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:31.013 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:31.017 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:31.017 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:31.017 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: suc,cess
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-22 14:39:32.619 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:32.619 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:5
2016-03-22 14:39:32.620 ThaliTest[1961:3347461] multipeer m,anager: start client restart timer: 0x1755d560
2016-03-22 14:39:32.621 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:5
2016-03-22 14:39:32.621 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
,ok 147 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 14:39:32.633 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:39:32.634 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
,2016-03-22 14:39:32.638 ThaliTest[1961:3347461] multipeer manager: stop client timer
,2016-03-22 14:39:32.645 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:6
,2016-03-22 14:39:32.648 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
,2016-03-22 14:39:32.654 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:6
,2016-03-22 14:39:32.656 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
,ok 148 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-03-22 14:39:33.582 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:39:33.585 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:33.589 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:33.589 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
,2016-03-22 14:39:33.591 ThaliTest[1961:3347461] multipeer manager: stop client timer
,2016-03-22 14:39:33.594 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-22 14:39:34.273 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:34.273 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:39:34.274 ThaliTest[1961:3347461] multipeer m,anager: start client restart timer: 0x1755d560
2016-03-22 14:39:34.275 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:39:34.275 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-22 14:39:34.279 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 14:39:34.281 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 152 Can call startListeningForAdvertisements without error
,2016-03-22 14:39:35.238 ThaliTest[1961:3347224] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:7
,ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-22 14:39:35.700 ThaliTest[1961:3347224] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
,2016-03-22 14:39:38.906 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:39:38.908 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:38.911 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:38.912 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:39:38.914 ThaliTest[1961:3347461] multipeer manager: stop client timer
2016-03-22 14:39:38.914 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
,ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-22 14:40:02.033 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:40:02.033 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:02.034 ThaliTest[1961:3347461] multipeer m,anager: start client restart timer: 0x1755d560
2016-03-22 14:40:02.034 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:02.034 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening: success
,ok 161 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 14:40:02.040 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-22 14:40:02.042 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 162 Can call startListeningForAdvertisements without error
,2016-03-22 14:40:03.953 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:03.954 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF0,83690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:40:04.017 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:04.017 ThaliTest[1961:3347224] server: rejecting invitation for lexical ordering 46287C39-66D9-4C88-AB7B-A74C4F9B045C
INFO testThaliMobileNative: Received pee,rAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"46287C39-66D9-4C88-AB7B-A74C4F9B045C:8","pleaseConnect":1}]
,2016-03-22 14:40:04.021 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:40:04.023 ThaliTest[1961:3347461] client: unknown peer 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:04.024 ThaliTest[1961:3347461] jxcore: connect: fail: Unknown peer
INFO testThaliMobileNative: Connect returned an error: Unknown peer
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 14:40:04.068 ThaliTest[1961:3347224] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
2016-03-22 14:40:04.070 ThaliTest[1961:3347224] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"46287C39-66D9-4C88-AB7B-A74C4F9B045C:7","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:7","pleaseConnect":0}]
,2016-03-22 14:40:07.034 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:07.035 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:40:07.035 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
,2016-03-22 14:40:07.903 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:07.904 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:40:07.904 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:40:11.079 ThaliTest[1961:3347889] client session: p2p link connected
,2016-03-22 14:40:11.096 ThaliTest[1961:3347888] client session: stateChange:1->2 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
2016-03-22 14:40:11.097 ThaliTest[1961:3347888] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:40:11.097 ThaliTest[1961:3347888] jxcore: connect: success
,INFO testThaliMobileNative: 
,ok 163 Must have listeningPort
,ok 164 listeningPort must be a number
,ok 165 Connection must have clientPort
,ok 166 clientPort must be a number
,ok 167 Connection must have serverPort
,ok 168 serverPort must be a number
,ok 169 forward connection must have clientPort == 0
,ok 170 forward connection must have serverPort == 0
,# teardown
,2016-03-22 14:40:11.617 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:11.617 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:40:11.617 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:40:15.734 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:15.735 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:40:15.735 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:40:19.209 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:19.209 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:40:19.210 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:40:22.036 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:40:22.060 ThaliTest[1961:3347224] client: found updated peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:22.061 ThaliTest[1961:3347224] client: found updated peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"46287C39-66D9-4C88-AB7B-A74C4F9B045C:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8","pleaseConnect":0}]
,2016-03-22 14:40:42.036 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:40:42.061 ThaliTest[1961:3347224] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:42.063 ThaliTest[1961:3347224] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:40:58.336 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:40:58.337 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:40:58.337 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:41:01.501 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:01.502 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:01.502 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:41:02.036 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:41:02.065 ThaliTest[1961:3347224] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:02.065 ThaliTest[1961:3347224] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:41:05.042 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:05.043 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:05.043 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:41:08.236 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:08.237 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:08.237 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7)
,2016-03-22 14:41:09.658 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:41:09.660 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 171 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:41:09.663 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
2016-03-22 14:41:09.664 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:41:09.664 ThaliTest[1961:3347461] client session: disconnect
2016-03-22 14:41:09.665 ThaliTest[1961:3347461] client session: stateChange:2->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:09.676 ThaliTest[1961:3347461] multipeer manager: stop client timer
2016-03-22 14:41:09.676 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can shift large amounts of data
,2016-03-22 14:41:11.308 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:41:11.308 ThaliTest[1961:3347461] server: starting 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:41:11.309 ThaliTest[1961:3347461] multipeer m,anager: start client restart timer: 0x1755d560
2016-03-22 14:41:11.309 ThaliTest[1961:3347461] THEMultipeerManager initialized peer 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:41:11.310 ThaliTest[1961:3347461] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-22 14:41:11.312 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
,2016-03-22 14:41:11.316 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-22 14:41:11.324 ThaliTest[1961:3347224] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:11.325 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:11.325 ThaliTest[1961:3,347461] client session: connect
2016-03-22 14:41:11.326 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:12.425 ThaliTest[1961:3347224] multipeer session: reset timer
,2016-03-22 14:41:12.425 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:12.480 ThaliTest[1961:3348070] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:12.481 ThaliTest[1961:3348070] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:41:12.482 ThaliTest[1961:3348070] client session: disconnect
,2016-03-22 14:41:12.485 ThaliTest[1961:3348070] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:12.490 ThaliTest[1961:3348070] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 1,4:41:12.491 ThaliTest[1961:3348070] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 14:41:12.500 ThaliTest[1961:3347224] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:41:13.527 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:13.527 ThaliTest[1961:3347224] server: rejecting invitation from 46287C39-66D9-4C88-AB7B-A74C4F9B045C due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:15.503 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:15.504 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:15.505 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:15.636 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:15.636 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:15.636 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:16.088 ThaliTest[1961:3348070] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:16.089 ThaliTest[1961:3348070] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:41:16.089 ThaliTest[1961:3348070] client session: disconnect
2016-03-22 14:41:16.090 ThaliTest[1961:3348070] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:16.091 ThaliTest[1961:3348070] client sess,ion: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:16.091 ThaliTest[1961:3348070] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: ,Scheduling a connect retry - retries left: 8
,2016-03-22 14:41:18.754 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:18.754 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:18.755 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:19.097 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:19.098 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:19.098 ThaliTest[1961:3347461] client session: stateChange:0->,1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:19.813 ThaliTest[1961:3348071] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:19.814 ThaliTest[1961:3348071] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:41:19.814 ThaliTest[1961:3348071] client session: disconnect
2016-03-22 14:41:19.817 ThaliTest[1961:3348071] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:19.817 ThaliTest[1961:3348071] client sess,ion: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:19.818 ThaliTest[1961:3348071] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: ,Scheduling a connect retry - retries left: 7
,2016-03-22 14:41:21.870 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:21.870 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:21.871 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:22.831 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:22.832 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:22.833 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:23.416 ThaliTest[1961:3348071] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:23.417 ThaliTest[1961:3348071] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:23.4,17 ThaliTest[1961:3348071] client session: disconnect
2016-03-22 14:41:23.417 ThaliTest[1961:3348071] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:23.418 ThaliTest[1961:3348071] client session: fireConnectCallb,ack: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:23.419 ThaliTest[1961:3348071] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-03-22 14:41:25.012 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:25.012 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:25.013 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:25.651 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:25.652 ThaliTest[1961:3347224] server: disconnecting to refresh session (46287C39-66D9-4C88-AB7B-A74C4F9B045C)
2016-03-22 14:41:25.652 ThaliTest[1961:3347224], server: rejecting invitation from 46287C39-66D9-4C88-AB7B-A74C4F9B045C due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:26.425 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:26.426 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:26.426 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:27.154 ThaliTest[1961:3347889] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:27.154 ThaliTest[1961:3347889] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:27.1,54 ThaliTest[1961:3347889] client session: disconnect
2016-03-22 14:41:27.155 ThaliTest[1961:3347889] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:27.155 ThaliTest[1961:3347889] client session: fireConnectCallb,ack: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:27.156 ThaliTest[1961:3347889] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 14:41:28.146 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:28.146 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:28.147 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:30.164 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:30.165 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:30.165 ThaliTest[1961:3347461] client session: stateChange:0->,1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:30.765 ThaliTest[1961:3348099] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:30.766 ThaliTest[1961:3348099] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:30.767 ThaliTest[1961:3348099] client session: disconnect
2016-03-22 14:41:30.767 ThaliTest[1961:3348099] client session:, stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:30.768 ThaliTest[1961:3348099] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:30.768 ThaliTest[1961:3348099] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 14:41:31.290 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:31.290 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:41:31.290 ThaliTest[1961:3347224] server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:31.311 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:41:31.337 ThaliTest[1961:3347224] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:31.338 ThaliTest[1961:3347224] client: found updated peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
,2016-03-22 14:41:33.781 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:33.782 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:33.782 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:34.394 ThaliTest[1961:3348070] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:34.395 ThaliTest[1961:3348070] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:34.395 ThaliTest[1961:3348070] client session: disconnect
,2016-03-22 14:41:34.396 ThaliTest[1961:3348070] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:34.398 ThaliTest[1961:3348070] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:41:34.398 ThaliTest[1961:3348070] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-22 14:41:37.414 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:37.415 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:37.415 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:38.069 ThaliTest[1961:3348070] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:38.070 ThaliTest[1961:3348070] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:41:38.070 ThaliTest[1961:3348070] client session: disconnect
,2016-03-22 14:41:38.073 ThaliTest[1961:3348070] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:38.073 ThaliTest[1961:3348070] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:38.074 ThaliTest[1961:3348070] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 14:41:38.330 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:41:38.330 ThaliTest[1961:3347224] server: disconnecting to refresh session (46287C39-66D9-4C88-AB7B-A74C4F9B045C)
2016-03-22 14:41:38.331 ThaliTest[1961:3347224], server: rejecting invitation from 46287C39-66D9-4C88-AB7B-A74C4F9B045C due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:41:41.087 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:41.088 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:41.089 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:41.795 ThaliTest[1961:3348099] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:41.796 ThaliTest[1961:3348099] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:41.797 ThaliTest[1961:3348099] client session: disconnect
2016-03-22 14:41:41.797 ThaliTest[1961:3348099] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:41.799 ThaliTest[1961:3348099] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:41.800 ThaliTest[1961:3348099] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 14:41:44.807 ThaliTest[1961:3347461] jxcore: connect 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:44.808 ThaliTest[1961:3347461] client session: connect
2016-03-22 14:41:44.808 ThaliTest[1961:3347461] client session: stateChange:0->1 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:45.496 ThaliTest[1961:3348071] client session: not connected 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:45.497 ThaliTest[1961:3348071] client session: onLinkFailure: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:45.497 ThaliTest[1961:3348071] client session: disconnect
,2016-03-22 14:41:45.499 ThaliTest[1961:3348071] client session: stateChange:1->0 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:45.501 ThaliTest[1961:3348071] client session: fireConnectCallback: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
2016-03-22 14:41:45.501 ThaliTest[1961:3348071] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-22 14:41:51.311 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:41:51.337 ThaliTest[1961:3347224] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
2016-03-22 14:41:51.338 ThaliTest[1961:3347224] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:42:07.538 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:42:07.539 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:42:07.539 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:42:10.663 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:42:10.663 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:42:10.664 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:42:11.311 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:42:11.335 ThaliTest[1961:3347224] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:42:11.337 ThaliTest[1961:3347224] client: found existing peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
,2016-03-22 14:42:13.751 ThaliTest[1961:3347224] multipeer session: reset timer
2016-03-22 14:42:13.752 ThaliTest[1961:3347224] server: disconnecting to refresh session (E37C719D-F7A3-448B-B4C9-69FDBA30F0B4)
2016-03-22 14:42:13.752 ThaliTest[1961:3347224], server: rejecting invitation from E37C719D-F7A3-448B-B4C9-69FDBA30F0B4 due to previous generation (4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9 != 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8)
,2016-03-22 14:42:20.283 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:42:20.285 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
ok 176 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:42:20.288 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
,2016-03-22 14:42:20.289 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
2016-03-22 14:42:20.290 ThaliTest[1961:3347461] multipeer manager: stop client timer
2016-03-22 14:42:20.291 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
,ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-22 14:42:20.768 ThaliTest[1961:3347461] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:20.769 ThaliTest[1961:3347461] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:20.770 ThaliTest[1961:3347461] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:20.773 ThaliTest[1961:3347461] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 178 specific error should be returned
,# teardown
,# setup
,2016-03-22 14:42:22.310 ThaliTest[1961:3347461] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:22.311 ThaliTest[1961:3347461] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:22.312 ThaliTest[1961:3,347461] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:22.315 ThaliTest[1961:3347461] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 179 specific error should be returned
,# teardown
,# setup
,2016-03-22 14:42:22.962 ThaliTest[1961:3347461] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:22.963 ThaliTest[1961:3347461] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:22.963 ThaliTest[1961:3,347461] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:22.966 ThaliTest[1961:3347461] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50432
,2016-03-22 14:42:23.377 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:42:23.380 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 180 no errors
,2016-03-22 14:42:23.385 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:42:23.390 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,ok 181 still no errors
,# teardown
,2016-03-22 14:42:23.508 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening
,2016-03-22 14:42:23.509 ThaliTest[1961:3347461] THEMultipeerManager stopping peer
,2016-03-22 14:42:23.510 ThaliTest[1961:3347461] jxcore: stopAdvertisingAndListening: success
,2016-03-22 14:42:23.512 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:42:23.515 ThaliTest[1961:3347461] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-22 14:42:23.864 ThaliTest[1961:3347461] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:42:23.865 ThaliTest[1961:3347461] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 14:42:23.866 ThaliTest[1961:3347461] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:23.869 ThaliTest[1961:3347461] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50434
,2016-03-22 14:42:24.033 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
,2016-03-22 14:42:24.035 ThaliTest[1961:3347461] multipeer manager: start client restart timer: 0x1755d560
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:42:24.046 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 182 no errors
,2016-03-22 14:42:24.050 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:42:24.052 ThaliTest[1961:3347461] jxcore: startListeningForAdvertisements: success
,ok 183 still no errors
,# teardown
,2016-03-22 14:42:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:43:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:43:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:43:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:44:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:44:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:44:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:45:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:45:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:45:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:46:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:46:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:46:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:47:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:47:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:47:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:48:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:48:24.042 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:48:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:49:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:49:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:49:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:50:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:50:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:50:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:51:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:51:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:51:44.042 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:52:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:52:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:52:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:53:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:53:24.042 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:53:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:54:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:54:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:54:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:55:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:55:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:55:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:56:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:56:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:56:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:57:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:57:24.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:57:44.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:58:04.043 ThaliTest[1961:3347224] multipeer manager: restart client
,2016-03-22 14:58:24.043 ThaliTest[1961:3347224] multipeer manager: restart client

```
