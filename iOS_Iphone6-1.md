#### Test 67111490059a058_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/316AB5BC-2E54-4712-A27D-D1237D80397D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/316AB5BC-2E54-4712-A27D-D1237D80397D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54013"
,(lldb)     command script import "/tmp/316AB5BC-2E54-4712-A27D-D1237D80397D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-20 04:47:32.006 ThaliTest[3430:7625678] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A56D5BEE-F953-4F2D-8C34-2F45459116F9/Library/Cookies/Cookies.binarycookies
,2016-04-20 04:47:32.345 ThaliTest[3430:7625678] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-20 04:47:32.346 ThaliTest[3430:7625678] Multi-tasking -> Device: YES, App: YES
,2016-04-20 04:47:32.369 ThaliTest[3430:7625678] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-20 04:47:34.319 ThaliTest[3430:7625678] Using UIWebView
,2016-04-20 04:47:34.325 ThaliTest[3430:7625678] [CDVTimer][handleopenurl] 0.468969ms
,2016-04-20 04:47:34.333 ThaliTest[3430:7625678] [CDVTimer][intentandnavigationfilter] 7.209003ms
2016-04-20 04:47:34.334 ThaliTest[3430:7625678] [CDVTimer][gesturehandler] 0.348985ms
2016-04-20 04:47:34.334 ThaliTest[3430:7625678] [CDVTimer][TotalPluginS,tartup] 9.634018ms
,2016-04-20 04:47:41.872 ThaliTest[3430:7625678] Resetting plugins due to page load.
,2016-04-20 04:47:45.747 ThaliTest[3430:7625678] Finished load of: file:///var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/index.html
,2016-04-20 04:47:45.974 ThaliTest[3430:7625678] JXcore Cordova plugin initializing
,2016-04-20 04:47:45.975 ThaliTest[3430:7625920] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-20 04:47:53.420 ThaliTest[3430:7625920] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-20 04:47:53.420 ThaliTest[3430:7625920] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-20 04:47:53.421 ThaliTest[3430:7625920] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-20 04:47:53.423 ThaliTest[3430:7625920] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2BEE8F5-4F24-4427-9023-4FE4FCBBC2EB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-20 04:47:59.998 ThaliTest[3430:7625678] THREAD WARNING: ['JXcore'] took '6265.150879' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59641
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59643
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
,DEBUG createNativeListener: listening 59646
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
,DEBUG createNativeListener: listening 59650
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
,DEBUG createNativeListener: listening 59655
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
,DEBUG createNativeListener: listening 59659
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
,DEBUG createNativeListener: listening 59663
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
,DEBUG createNativeListener: listening 59667
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
,DEBUG createNativeListener: listening 59671
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
,DEBUG createNativeListener: listening 59723
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
,DEBUG createNativeListener: listening 59727
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
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"bfdc7c82-3e48-4c76-97f8-19cc4d017af4","data":"custom data"},{"uuid":"193381e1-e38b-4d7e-b0af-8de5815cb621","data":"custom data"},{"uuid":"06642e6b-b55e-487b-9d1a-ac467e3aa68a","data":"custom data"},{"uuid":"da57b363-146c-4326-bcf1-87fd4d08657a",",data":"custom data"}]
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
,DEBUG createNativeListener: listening 59737
,2016-04-20 04:50:07.036 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:07.038 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-20 04:50:07.040 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:07.041 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-20 04:50:07.121 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:07.121 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:07.121 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-20 04:50:07.122 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:07.122 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59739
,2016-04-20 04:50:07.325 ThaliTest[3430:7625920] jxcore: startListeningForAdvertisements
,2016-04-20 04:50:07.326 ThaliTest[3430:7625920] multipeer manager: start client restart timer: 0x16ddb3f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:07.328 ThaliTest[3430:7625920] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-20 04:50:07.341 ThaliTest[3430:7625920] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:07.342 ThaliTest[3430:7625920] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-20 04:50:07.641 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:07.642 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:07.643 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: success
2016-04-20 04:50:07.644 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
,2016-04-20 04:50:07.646 ThaliTest[3430:7625920] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:07.649 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59741
,2016-04-20 04:50:08.186 ThaliTest[3430:7625920] jxcore: startUpdateAdvertisingAndListening
,2016-04-20 04:50:08.188 ThaliTest[3430:7625920] server: starting DF7D62F5-96D1-401F-B736-926B7A8C54F1:1
,2016-04-20 04:50:08.189 ThaliTest[3430:7625920] multipeer manager: start client restart timer: 0x16ddb3f0
2016-04-20 04:50:08.190 ThaliTest[3430:7625920] THEMultipeerManager initialized peer DF7D62F5-96D1-401F-B736-926B7A8C54F1:1
2016-04-20 04:50:08.190 ThaliTest[3430:7625920] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-20 04:50:08.210 ThaliTest[3430:7625920] jxcore: startUpdateAdvertisingAndListening
2016-04-20 04:50:08.211 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:08.211 ThaliTest[3430:7625920] multipeer manager: stop client ti,mer
2016-04-20 04:50:08.212 ThaliTest[3430:7625920] server: starting DF7D62F5-96D1-401F-B736-926B7A8C54F1:2
2016-04-20 04:50:08.212 ThaliTest[3430:7625920] multipeer manager: start client restart timer: 0x16ddb3f0
2016-04-20 04:50:08.213 ThaliTest[3430:,7625920] THEMultipeerManager initialized peer DF7D62F5-96D1-401F-B736-926B7A8C54F1:2
2016-04-20 04:50:08.217 ThaliTest[3430:7625920] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-20 04:50:09.218 ThaliTest[3430:7625678] client: found new peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:2
,2016-04-20 04:50:09.496 ThaliTest[3430:7625678] client: found new peer: 98501501-ECD9-4428-8F6B-7983BCB3CA3C:2
,2016-04-20 04:50:09.836 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:09.837 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:09.837 ThaliTest[3430:7625920] multipeer manager: stop client timer
,2016-04-20 04:50:09.839 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: success
,2016-04-20 04:50:09.840 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:09.844 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59746
,2016-04-20 04:50:51.071 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.071 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:51.071 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-20 04:50:51.077 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.077 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:51.078 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-20 04:50:51.159 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.160 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:51.160 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: success
2016-04-20 04:50:51.161 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:51.164 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59748
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-20 04:50:51.487 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:51.487 ThaliTest[3430:7625920] THEMultipeerManager stopping peer
2016-04-20 04:50:51.487 ThaliTest[3430:7625920] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-20 04:50:51.488 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:51.490 ThaliTest[3430:7625920] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59750
,2016-04-20 04:50:51.688 ThaliTest[3430:7625920] jxcore: startListeningForAdvertisements
2016-04-20 04:50:51.689 ThaliTest[3430:7625920] multipeer manager: start client restart timer: 0x16ddb3f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:51.693 ThaliTest[3430:7625920] jxcore: startListeningForAdvertisements: success
,2016-04-20 04:50:51.726 ThaliTest[3430:7625920] jxcore: startUpdateAdvertisingAndListening
2016-04-20 04:50:51.726 ThaliTest[3430:7625920] server: starting DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:50:51.728 ThaliTest[3430:7625920] THEMultipeerManager initialized peer DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:50:51.730 ThaliTest[3430:7625920] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-20 04:50:52.413 ThaliTest[3430:7625678] client: found new peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:2
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:50:53.762 ThaliTest[3430:7625678] client: found new peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:51:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:51:11.713 ThaliTest[3430:7625678] client: found updated peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:51:11.714 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:51:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:51:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:51:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:51:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:52:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:52:11.718 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:52:11.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:52:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:52:31.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:52:31.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:52:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:52:51.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:52:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:53:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:53:11.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:53:11.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:53:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:53:31.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:53:31.721 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:53:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:53:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:53:51.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:54:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:54:11.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:54:11.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:54:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:54:31.718 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:54:31.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:54:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:54:51.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:54:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:55:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:55:11.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:55:11.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:55:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:55:31.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:55:31.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:55:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:55:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:55:51.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:56:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:56:11.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:56:11.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:56:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:56:31.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:56:31.721 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:56:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:56:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:56:51.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:57:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:57:11.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:57:11.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:57:31.690 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:57:31.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:57:31.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:57:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:57:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:57:51.720 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:58:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:58:11.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:58:11.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:58:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:58:31.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:58:31.716 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:58:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:58:51.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:58:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:59:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:59:11.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:59:11.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:59:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:59:31.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:59:31.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:59:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 04:59:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:59:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:00:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:00:11.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:00:11.716 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:00:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:00:31.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:00:31.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:00:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:00:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:00:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:01:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:01:11.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 05:01:11.718 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:01:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:01:31.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:01:31.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:01:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:01:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:01:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:02:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:02:11.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:02:11.722 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:02:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:02:31.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:02:31.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:02:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:02:51.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:02:51.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:03:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:03:11.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:03:11.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:03:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:03:31.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:03:31.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:03:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:03:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 05:03:51.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:04:11.690 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:04:11.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:04:11.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:04:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:04:31.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 05:04:31.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:04:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:04:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:04:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:05:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:05:11.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:05:11.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:05:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:05:31.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 05:05:31.718 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:05:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:05:51.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:05:51.716 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:06:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:06:11.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:06:11.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:06:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:06:31.720 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:06:31.721 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:06:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:06:51.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:06:51.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:07:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:07:11.719 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:07:11.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:07:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:07:31.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:07:31.720 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:07:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:07:51.716 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:07:51.718 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:08:11.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:08:11.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:08:11.719 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:08:31.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:08:31.715 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:08:31.715 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 05:08:51.691 ThaliTest[3430:7625678] multipeer manager: restart client
,2016-04-20 05:08:51.717 ThaliTest[3430:7625678] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:08:51.717 ThaliTest[3430:7625678] client: found existing peer: A1C44B62-F329-4704-A7A7-5D86DB1D6308:3

```
