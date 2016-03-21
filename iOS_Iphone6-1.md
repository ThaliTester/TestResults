#### Test 625481240f1d9b8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0BE54C13-0A23-4ED8-A327-627C99B69B42/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0BE54C13-0A23-4ED8-A327-627C99B69B42/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481240f1d9b8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54442"
,(lldb)     command script import "/tmp/0BE54C13-0A23-4ED8-A327-627C99B69B42/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 16:43:50.625 ThaliTest[1907:3212545] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8DD156B0-A541-4C18-AA46-90B04105290E/Library/Cookies/Cookies.binarycookies
,2016-03-21 16:43:51.039 ThaliTest[1907:3212545] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 16:43:51.041 ThaliTest[1907:3212545] Multi-tasking -> Device: YES, App: YES
,2016-03-21 16:43:51.063 ThaliTest[1907:3212545] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 16:43:52.906 ThaliTest[1907:3212545] Using UIWebView
,2016-03-21 16:43:52.913 ThaliTest[1907:3212545] [CDVTimer][handleopenurl] 0.595033ms
,2016-03-21 16:43:52.922 ThaliTest[1907:3212545] [CDVTimer][intentandnavigationfilter] 8.201003ms
2016-03-21 16:43:52.923 ThaliTest[1907:3212545] [CDVTimer][gesturehandler] 0.418007ms
2016-03-21 16:43:52.923 ThaliTest[1907:3212545] [CDVTimer][TotalPluginStartup] 10.873020ms
,2016-03-21 16:43:59.847 ThaliTest[1907:3212545] Resetting plugins due to page load.
,2016-03-21 16:44:03.261 ThaliTest[1907:3212545] Finished load of: file:///var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/index.html
,2016-03-21 16:44:03.484 ThaliTest[1907:3212545] JXcore Cordova plugin initializing
2016-03-21 16:44:03.485 ThaliTest[1907:3212741] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 16:44:10.722 ThaliTest[1907:3212741] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 16:44:10.722 ThaliTest[1907:3212741] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 16:44:10.723 ThaliTest[1907:3212741] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 16:44:10.725 ThaliTest[1907:3212741] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B44F7A03-806D-4A87-9779-B19206C16DA4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 16:44:16.547 ThaliTest[1907:3212545] THREAD WARNING: ['JXcore'] took '5510.963867' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49773
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49776
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
,DEBUG createNativeListener: listening 49779
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
,DEBUG createNativeListener: listening 49783
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
,DEBUG createNativeListener: listening 49788
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
,DEBUG createNativeListener: listening 49793
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
,DEBUG createNativeListener: listening 49797
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
,DEBUG createNativeListener: listening 49801
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
,DEBUG createNativeListener: listening 49805
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
,DEBUG createNativeListener: listening 49857
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
,DEBUG createNativeListener: listening 49861
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
,DEBUG createNativeListener: listening 49873
,2016-03-21 16:46:12.110 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:12.113 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 16:46:12.118 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:12.120 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 16:46:12.214 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:12.214 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:12.215 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
,2016-03-21 16:46:12.217 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:12.219 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49875
,2016-03-21 16:46:12.557 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
,2016-03-21 16:46:12.559 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 16:46:12.562 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
ok 89 error should be null
,2016-03-21 16:46:12.576 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 16:46:12.579 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 16:46:12.819 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:12.820 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:12.820 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
2016-03-21 16:46:12.821 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
2016-03-21 16:46:12.821 ThaliTest[1907:3212741] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 16:46:12.826 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49877
,2016-03-21 16:46:13.349 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 16:46:13.351 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:1
,2016-03-21 16:46:13.352 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:13.353 ThaliTest[1907:3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:1
2016-03-21 16:46:13.354 ,ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-21 16:46:13.372 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:13.372 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:13.373 ThaliTest[1907:3212741] multipeer manager: stop client ti,mer
2016-03-21 16:46:13.374 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:2
2016-03-21 16:46:13.375 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:13.376 ThaliTest[1907:,3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:2
2016-03-21 16:46:13.376 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-21 16:46:13.578 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:13.579 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:13.579 ThaliTest[1907:3212741] multipeer manager: stop client timer
,2016-03-21 16:46:13.581 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
2016-03-21 16:46:13.582 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:13.585 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49882
,2016-03-21 16:46:14.403 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:14.404 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:14.404 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 100 error should be null
,ok 101 error should be null
,2016-03-21 16:46:14.410 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:14.411 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:14.411 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: suc,cess
ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-21 16:46:14.565 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:14.566 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:14.566 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
2016-03-21 16:46:14.567 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:14.570 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49884
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 16:46:15.573 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:15.573 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:15.573 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
2016-03-21 16:46:15.574 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:15.577 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49886
,2016-03-21 16:46:15.998 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
2016-03-21 16:46:15.999 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 16:46:16.002 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,2016-03-21 16:46:16.022 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:16.022 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:3
2016-03-21 16:46:16.023 ThaliTest[1907:3212741] THEMultipee,rManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:3
2016-03-21 16:46:16.023 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-21 16:46:16.158 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:16.159 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:16.159 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 16:46:16.160 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,2016-03-21 16:46:16.160 ThaliTest[1907:3212741] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:16.167 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
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
,2016-03-21 16:46:21.292 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
2016-03-21 16:46:21.293 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:21.294 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-21 16:46:21.296 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
2016-03-21 16:46:21.298 ThaliTest[1907:3212741] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-21 16:46:21.300 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 16:46:21.729 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:21.731 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:21.734 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:21.734 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:21.735 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 16:46:22.850 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
2016-03-21 16:46:22.851 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:22.853 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-21 16:46:22.857 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 16:46:22.859 ThaliTest[1907:32127,41] jxcore: startListeningForAdvertisements: success
ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 16:46:23.843 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
2016-03-21 16:46:23.844 ThaliTest[1907:3212741] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:23.846 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-21 16:46:23.849 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:23.850 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:23.850 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 16:46:24.408 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:24.409 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:4
2016-03-21 16:46:24.410 ThaliTest[1907:3212741] multipeer m,anager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:24.410 ThaliTest[1907:3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:4
2016-03-21 16:46:24.410 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-21 16:46:24.412 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:24.413 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016,-03-21 16:46:24.413 ThaliTest[1907:3212741] multipeer manager: stop client timer
2016-03-21 16:46:24.414 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-21 16:46:24.755 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 16:46:24.758 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:24.761 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:24.761 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:24.762 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 16:46:25.301 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:25.301 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:5
2016-03-21 16:46:25.302 ThaliTest[1907:3212741] multipeer m,anager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:25.303 ThaliTest[1907:3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:5
2016-03-21 16:46:25.303 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 16:46:25.305 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:25.306 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
,2016-03-21 16:46:25.307 ThaliTest[1907:3212741] multipeer manager: stop client timer
,2016-03-21 16:46:25.308 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:6
2016-03-21 16:46:25.309 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:25.309 ThaliTest[1907:32127,41] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:6
2016-03-21 16:46:25.310 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
# ,setup
,2016-03-21 16:46:25.460 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 16:46:25.462 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:25.465 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:25.466 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:25.466 ThaliTest[1907:3212741] multipeer manager: stop client timer
2016-03-21 16:46:25.466 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 16:46:26.251 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:26.252 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:26.252 ThaliTest[1907:3212741] multipeer m,anager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:26.253 ThaliTest[1907:3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7
2016-03-21 16:46:26.253 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-21 16:46:26.255 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 16:46:26.259 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 16:46:27.337 ThaliTest[1907:3212545] client: found new peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
ok 147 peers must be an array
,ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 16:46:28.577 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 16:46:28.580 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:46:28.583 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:46:28.583 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:46:28.584 ThaliTest[1907:3212741] multipeer manager: stop client timer
20,16-03-21 16:46:28.584 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 16:46:31.116 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
2016-03-21 16:46:31.117 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:46:31.117 ThaliTest[1907:3212741] multipeer m,anager: start client restart timer: 0x14d5f6e0
2016-03-21 16:46:31.118 ThaliTest[1907:3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8
2016-03-21 16:46:31.118 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-21 16:46:31.120 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-21 16:46:31.122 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 16:46:31.969 ThaliTest[1907:3212545] client: found new peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2EB617D0-DF93-4CC9-AB67-E3573BAE4,4B5:7","pleaseConnect":0}]
2016-03-21 16:46:31.972 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:31.973 ThaliTest[1907:3212741] client session: connect
,2016-03-21 16:46:31.973 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:33.514 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:46:33.514 ThaliTest[1907:3212545] server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:46:33.540 ThaliTest[1907:3213813] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:33.541 ThaliTest[1907:3213813] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
,2016-03-21 16:46:33.542 ThaliTest[1907:3213813] client session: disconnect
,2016-03-21 16:46:33.543 ThaliTest[1907:3213813] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:33.545 ThaliTest[1907:3213813] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:33.545 ThaliTest[1907:3213813] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 16:46:36.553 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:36.553 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:36.554 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:37.123 ThaliTest[1907:3213846] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:37.126 ThaliTest[1907:3213846] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:37.126 ThaliTest[1907:3213846] client session: disconnect
2016-03-21 16:46:37.127 ThaliTest[1907:3213846] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:37.128 ThaliTest[1907:3213846] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:37.129 ThaliTest[1907:3213846] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 16:46:40.139 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:40.140 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:40.140 ThaliTest[1907:3212741] client session: stateChange:0->,1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:40.797 ThaliTest[1907:3213846] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:40.799 ThaliTest[1907:3213846] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:40.7,99 ThaliTest[1907:3213846] client session: disconnect
2016-03-21 16:46:40.799 ThaliTest[1907:3213846] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:40.800 ThaliTest[1907:3213846] client session: fireConnectCallb,ack: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:40.800 ThaliTest[1907:3213846] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-03-21 16:46:43.807 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:43.808 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:43.808 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:44.412 ThaliTest[1907:3213846] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:44.413 ThaliTest[1907:3213846] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:44.413 ThaliTest[1907:3213846] client session: disconnect
,2016-03-21 16:46:44.414 ThaliTest[1907:3213846] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:44.416 ThaliTest[1907:3213846] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 1,6:46:44.416 ThaliTest[1907:3213846] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 16:46:47.037 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:46:47.038 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:46:47.038 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:46:47.420 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:47.420 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:47.421 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:47.528 ThaliTest[1907:3213846] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:47.528 ThaliTest[1907:3213846] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:47.529 ThaliTest[1907:3213846] client session: disconnect
,2016-03-21 16:46:47.529 ThaliTest[1907:3213846] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:47.531 ThaliTest[1907:3213846] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:47.531 ThaliTest[1907:3213846] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 16:46:50.544 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:50.544 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:50.545 ThaliTest[1907:3212741] client session: stateChange:0->,1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:50.751 ThaliTest[1907:3213813] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:50.751 ThaliTest[1907:3213813] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
,2016-03-21 16:46:50.751 ThaliTest[1907:3213813] client session: disconnect
,2016-03-21 16:46:50.752 ThaliTest[1907:3213813] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
,2016-03-21 16:46:50.754 ThaliTest[1907:3213813] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
,2016-03-21 16:46:50.754 ThaliTest[1907:3213813] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 16:46:51.119 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:46:51.137 ThaliTest[1907:3212545] client: found updated peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8","pleaseConnect":0}]
,2016-03-21 16:46:53.760 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:53.760 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:53.761 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:46:53.853 ThaliTest[1907:3213846] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:46:53.854 ThaliTest[1907:3213846] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:53.855 ThaliTest[1907:3213846] client session: disconnect
2016-03-21 16:46:53.855 ThaliTest[1907:3213846] client session:, stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:46:53.856 ThaliTest[1907:3213846] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:53.856 ThaliTest[1907:3213846] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 16:46:56.860 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:46:56.861 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:46:56.861 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:46:57.040 ThaliTest[1907:3213813] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:46:57.041 ThaliTest[1907:3213813] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:57.0,41 ThaliTest[1907:3213813] client session: disconnect
2016-03-21 16:46:57.041 ThaliTest[1907:3213813] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:46:57.044 ThaliTest[1907:3213813] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:46:57.045 ThaliTest[1907:3213813] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 16:46:59.505 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:46:59.506 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:46:59.506 ThaliTest[1907:3212545] server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:47:00.060 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:47:00.061 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:47:00.061 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:47:00.188 ThaliTest[1907:3213813] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:47:00.188 ThaliTest[1907:3213813] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:47:00.1,88 ThaliTest[1907:3213813] client session: disconnect
2016-03-21 16:47:00.188 ThaliTest[1907:3213813] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:47:00.190 ThaliTest[1907:3213813] client session: fireConnectCallb,ack: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:47:00.191 ThaliTest[1907:3213813] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 16:47:03.205 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:7
2016-03-21 16:47:03.205 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:47:03.206 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:47:03.312 ThaliTest[1907:3213813] client session: not connected 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
2016-03-21 16:47:03.312 ThaliTest[1907:3213813] client session: onLinkFailure: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:47:03.312 ThaliTest[1907:3213813] client session: disconnect
,2016-03-21 16:47:03.312 ThaliTest[1907:3213813] client session: stateChange:1->0 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:47:03.316 ThaliTest[1907:3213813] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 16:47:03.317 ThaliTest[1907:3213813] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 16:47:11.119 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:47:11.137 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:47:12.363 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:47:12.363 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
,2016-03-21 16:47:12.364 ThaliTest[1907:3212545] server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:47:25.525 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:47:25.526 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:47:25.526 ThaliTest[1907:3212545] server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:47:31.119 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:47:31.136 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:47:38.576 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:47:38.576 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:47:38.576 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:47:51.119 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:47:51.138 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:47:51.614 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:47:51.615 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:47:51.615 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:48:04.723 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:48:04.723 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:48:04.724 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:48:11.119 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:48:11.139 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:48:17.763 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:48:17.763 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:48:17.764 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:48:30.990 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:48:30.990 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:48:30.991 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:7)
,2016-03-21 16:48:31.119 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:48:31.137 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,2016-03-21 16:48:41.007 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 16:48:41.009 ThaliTest[1907:3212741] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 16:48:41.012 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening
2016-03-21 16:48:41.012 ThaliTest[1907:3212741] THEMultipeerManager stopping peer
2016-03-21 16:48:41.013 ThaliTest[1907:3212741] multipeer manager: stop client timer
2016-03-21 16:48:41.013 ThaliTest[1907:3212741] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-21 16:48:42.746 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 16:48:42.747 ThaliTest[1907:3212741] server: starting 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:48:42.749 ThaliTest[1907:3212741] multipeer manager: start client restart timer: 0x14d5f6e0
,2016-03-21 16:48:42.763 ThaliTest[1907:3212741] THEMultipeerManager initialized peer 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9
,2016-03-21 16:48:42.766 ThaliTest[1907:3212741] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-21 16:48:42.769 ThaliTest[1907:3212545] client: found new peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:8
,ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 16:48:42.773 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-21 16:48:42.775 ThaliTest[1907:3212741] jxcore: startListeningForAdvertisements: success
,ok 161 Can call startListeningForAdvertisements without error
,2016-03-21 16:48:44.607 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:48:44.607 ThaliTest[1907:3212545] server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8)
,2016-03-21 16:48:55.570 ThaliTest[1907:3212545] multipeer session: reset timer
2016-03-21 16:48:55.570 ThaliTest[1907:3212545] server: disconnecting to refresh session (2EB617D0-DF93-4CC9-AB67-E3573BAE44B5)
2016-03-21 16:48:55.571 ThaliTest[1907:3212545], server: rejecting invitation from 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5 due to previous generation (75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:9 != 75CF4C6C-ED3C-4F8C-A623-CB08A4F1A8F1:8)
,2016-03-21 16:49:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:49:02.781 ThaliTest[1907:3212545] client: found updated peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
2016-03-21 16:49:02.783 ThaliTest[1907:3212741] jxcore: connect 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
2016-03-21 16:49:02.784 ThaliTest[1907:3212741] client session: connect
2016-03-21 16:49:02.784 ThaliTest[1907:3212741] client session: stateChange:0->1 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:49:05.695 ThaliTest[1907:3214360] client session: p2p link connected
,2016-03-21 16:49:05.830 ThaliTest[1907:3214362] client session: stateChange:1->2 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
2016-03-21 16:49:05.830 ThaliTest[1907:3214362] client session: fireConnectCallback: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5
2016-03-21 1,6:49:05.830 ThaliTest[1907:3214362] jxcore: connect: success
INFO testThaliMobileNative: 
INFO testThaliMobileNative: Forward connection
,2016-03-21 16:49:05.837 ThaliTest[1907:3212545] client: relay established
2016-03-21 16:49:05.838 ThaliTest[1907:3212545] client: new accepted socket: 0x17422a90
,INFO testThaliMobileNative: forwardSend
,INFO testThaliMobileNative: forwardData
,ok 162 received should match sent forward
,# setup
,2016-03-21 16:49:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:49:22.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:49:42.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:49:42.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:50:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:50:02.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:50:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:50:22.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:50:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:50:42.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:51:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:51:02.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:51:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:51:22.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:51:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:51:42.784 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:52:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:52:02.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:52:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:52:22.784 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:52:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:52:42.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:53:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:53:02.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:53:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:53:22.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:53:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:53:42.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:54:02.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:54:02.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:54:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:54:22.786 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:54:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:54:42.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:55:02.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:55:02.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:55:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:55:22.780 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:55:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:55:42.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:56:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:56:02.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:56:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:56:22.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:56:42.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:56:42.780 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:57:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:57:02.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:57:22.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:57:22.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:57:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:57:42.786 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:58:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:58:02.784 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:58:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:58:22.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:58:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:58:42.784 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:59:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:59:02.780 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:59:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:59:22.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 16:59:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 16:59:42.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:00:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:00:02.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:00:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:00:22.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:00:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:00:42.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:01:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:01:02.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:01:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:01:22.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:01:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:01:42.785 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:02:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:02:02.785 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:02:22.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:02:22.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:02:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:02:42.783 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:03:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:03:02.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:03:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:03:22.784 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:03:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:03:42.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:04:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:04:02.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:04:22.764 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:04:22.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:04:42.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:04:42.781 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:05:02.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:05:02.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9
,2016-03-21 17:05:22.765 ThaliTest[1907:3212545] multipeer manager: restart client
,2016-03-21 17:05:22.782 ThaliTest[1907:3212545] client: found existing peer: 2EB617D0-DF93-4CC9-AB67-E3573BAE44B5:9

```
