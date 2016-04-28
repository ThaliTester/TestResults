#### Test 681021307227906_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/137A7C9D-8A7C-42AC-A1F8-CFCEC03FFED9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/137A7C9D-8A7C-42AC-A1F8-CFCEC03FFED9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55109"
,(lldb)     command script import "/tmp/137A7C9D-8A7C-42AC-A1F8-CFCEC03FFED9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 21:24:52.054 ThaliTest[1342:3977633] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D138AE94-ADC1-462E-8331-7BF59CC4D0FB/Library/Cookies/Cookies.binarycookies
,2016-04-28 21:24:52.299 ThaliTest[1342:3977633] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-28 21:24:52.300 ThaliTest[1342:3977633] Multi-tasking -> Device: YES, App: YES
,2016-04-28 21:24:52.313 ThaliTest[1342:3977633] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 21:24:53.120 ThaliTest[1342:3977633] Using UIWebView
,2016-04-28 21:24:53.123 ThaliTest[1342:3977633] [CDVTimer][handleopenurl] 0.118971ms
,2016-04-28 21:24:53.125 ThaliTest[1342:3977633] [CDVTimer][intentandnavigationfilter] 1.924992ms
2016-04-28 21:24:53.125 ThaliTest[1342:3977633] [CDVTimer][gesturehandler] 0.104964ms
2016-04-28 21:24:53.125 ThaliTest[1342:3977633] [CDVTimer][TotalPluginStartup] 2.613008ms
,2016-04-28 21:24:58.316 ThaliTest[1342:3977633] Resetting plugins due to page load.
,2016-04-28 21:25:02.268 ThaliTest[1342:3977633] Finished load of: file:///var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/index.html
,2016-04-28 21:25:02.403 ThaliTest[1342:3977633] JXcore Cordova plugin initializing
,2016-04-28 21:25:02.404 ThaliTest[1342:3977817] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 21:25:08.930 ThaliTest[1342:3977817] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-28 21:25:08.930 ThaliTest[1342:3977817] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-28 21:25:08.931 ThaliTest[1342:3977817] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 21:25:08.932 ThaliTest[1342:3977817] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2CDD060A-C68F-49C9-87E0-E3256F8ACF88/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 21:25:14.171 ThaliTest[1342:3977633] THREAD WARNING: ['JXcore'] took '4966.212158' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54773
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54775
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
,DEBUG createNativeListener: listening 54778
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
,DEBUG createNativeListener: listening 54782
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
,DEBUG createNativeListener: listening 54787
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
,DEBUG createNativeListener: listening 54791
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
,DEBUG createNativeListener: listening 54795
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
,DEBUG createNativeListener: listening 54799
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
,DEBUG createNativeListener: listening 54803
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: listening 54855
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
,DEBUG createNativeListener: listening 54859
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
,[{"uuid":"12b0fe5c-5358-4bd1-a579-798f1c8d590d","data":"custom data"},{"uuid":"199e0e2c-9092-4104-af67-e71ad2ae16f8","data":"custom data"},{"uuid":"749167e2-4f0b-4861-8dc7-f1c6b8b47666","data":"custom data"},{"uuid":"76d70763-019d-486c-be48-b3480c768092","data":"custom data"}]
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
,DEBUG createNativeListener: listening 54869
,2016-04-28 21:27:55.036 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:55.038 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
ok 92 error should be null
2016-04-28 21:27:55.042 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:55.043 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-28 21:27:55.134 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:55.135 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:55.135 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:27:55.137 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:55.139 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54871
,2016-04-28 21:27:55.381 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,2016-04-28 21:27:55.382 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:55.386 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-28 21:27:55.410 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:55.412 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-28 21:27:55.656 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:55.657 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:55.657 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:27:55.659 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,2016-04-28 21:27:55.660 ThaliTest[1342:3977817] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:55.663 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54873
,2016-04-28 21:27:56.172 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
,2016-04-28 21:27:56.172 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:1
,2016-04-28 21:27:56.174 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
,2016-04-28 21:27:56.174 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:1
,2016-04-28 21:27:56.176 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-28 21:27:56.214 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
,2016-04-28 21:27:56.214 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:56.215 ThaliTest[1342:3977817] multipeer manager: stop client timer
2016-04-28 21:27:56.216 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:2
,2016-04-28 21:27:56.219 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
2016-04-28 21:27:56.220 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:2
2016-04-28 21:27:56.220 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-28 21:27:56.693 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:56.694 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:56.696 ThaliTest[1342:3977817] multipeer manager: stop client timer
,2016-04-28 21:27:56.698 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:27:56.699 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:56.702 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54878
,2016-04-28 21:27:57.437 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:57.437 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:57.438 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-28 21:27:57.443 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:57.444 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:57.444 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-28 21:27:58.251 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:58.252 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:27:58.252 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:27:58.254 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:58.256 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54880
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-28 21:28:03.395 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:03.395 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:28:03.396 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:28:03.397 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:03.399 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54882
,2016-04-28 21:28:03.601 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,2016-04-28 21:28:03.602 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-28 21:28:03.605 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
,2016-04-28 21:28:03.631 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:03.632 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:3
,2016-04-28 21:28:03.633 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:3
2016-04-28 21:28:03.633 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-28 21:28:03.847 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:03.848 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:28:03.848 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:28:03.850 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:03.851 ThaliTest[1342:3977817] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:03.854 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,2016-04-28 21:28:11.790 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,2016-04-28 21:28:11.792 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:11.795 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
,2016-04-28 21:28:11.799 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,2016-04-28 21:28:11.800 ThaliTest[1342:3977817] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:11.803 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:12.110 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:12.113 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:12.115 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:12.116 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:28:12.116 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-28 21:28:12.673 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,2016-04-28 21:28:12.674 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-28 21:28:12.677 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-28 21:28:12.680 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:12.683 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-28 21:28:14.659 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:14.660 ThaliTest[1342:3977817] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:14.663 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:14.667 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:14.667 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:28:14.668 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-28 21:28:29.411 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:29.413 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-28 21:28:29.416 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:29.418 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:29.559 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:29.561 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:29.563 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:29.564 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:28:29.564 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-28 21:28:29.855 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
,2016-04-28 21:28:29.856 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:4
,2016-04-28 21:28:29.858 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
2016-04-28 21:28:29.858 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:4
2016-04-28 21:28:29.859 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:29.863 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:29.864 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:29.864 ThaliTest[1342:3977817] multipeer manager: stop client timer
2016-04-28 21:28:29.864 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-28 21:28:30.158 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:30.161 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:30.163 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:30.163 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:28:30.164 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-28 21:28:33.852 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
,2016-04-28 21:28:33.853 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:5
,2016-04-28 21:28:33.854 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
2016-04-28 21:28:33.854 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:5
2016-04-28 21:28:33.855 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:33.858 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:33.859 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:33.859 ThaliTest[1342:3977817] multipeer manager: stop client ti,mer
2016-04-28 21:28:33.859 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:6
2016-04-28 21:28:33.860 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
2016-04-28 21:28:33.861 ThaliTest[1342:,3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:6
2016-04-28 21:28:33.861 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without erro,r
,# teardown
,2016-04-28 21:28:34.958 ThaliTest[1342:3977633] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:6
,2016-04-28 21:28:35.239 ThaliTest[1342:3977633] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:6
,2016-04-28 21:28:36.956 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:28:36.957 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:36.958 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.958 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:36.958 ThaliTest[1342:3977817] multipeer manager: stop client timer
20,16-04-28 21:28:36.958 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-28 21:28:37.716 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:37.717 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:37.717 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: suc,cess
,ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:28:37.717 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:37.717 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:37.718 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-28 21:28:39.621 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:28:39.622 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:39.623 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:39.623 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:39.623 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-28 21:28:57.666 ThaliTest[1342:3977817] jxcore: connect foo
2016-04-28 21:28:57.667 ThaliTest[1342:3977817] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-28 21:28:57.967 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:57.968 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:57.968 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:57.969 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:28:57.969 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-28 21:29:01.017 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:01.017 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
2016-04-28 21:29:01.017 ThaliTest[1342:3977817] multipeer m,anager: start client restart timer: 0x15692220
2016-04-28 21:29:01.017 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:01.018 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-28 21:29:01.019 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-28 21:29:01.021 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdve,rtisements without error
,2016-04-28 21:29:02.590 ThaliTest[1342:3977633] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
,ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-28 21:29:02.650 ThaliTest[1342:3977633] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:03.362 ThaliTest[1342:3977633] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:6
,2016-04-28 21:29:04.161 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:29:04.162 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:29:04.163 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
2016-04-28 21:29:04.163 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
2016-04-28 21:29:04.163 ThaliTest[1342:3977817] multipeer manager: stop client timer
20,16-04-28 21:29:04.163 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-28 21:29:06.084 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:06.084 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:29:06.084 ThaliTest[1342:3977817] multipeer manager: start client restart timer: 0x15692220
2016-04-28 21:29:06.085 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:06.085 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:29:06.086 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-28 21:29:06.087 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:06.143 ThaliTest[1342:3977633] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:06.144 ThaliTest[1342:3977633] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59A7B25203:7","pleaseConnect":0}]
2016-04-28 21:29:06.144 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:06.145 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:29:06.145 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7","pleaseConnect":0}]
,2016-04-28 21:29:06.964 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:06.964 ThaliTest[1342:3977633] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:07.044 ThaliTest[1342:3977633] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:7","pleaseConnect":0}]
,2016-04-28 21:29:07.227 ThaliTest[1342:3978386] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:07.228 ThaliTest[1342:3978386] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:07.228 ThaliTest[1342:3978386] client session: disconnect
2016-04-28 21:29:07.228 ThaliTest[1342:3978386] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:07.229 ThaliTest[1342:3978386] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:07.229 ThaliTest[1342:3978386] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:29:07.490 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:07.490 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4,125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:10.236 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:10.237 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:29:10.237 ThaliTest[1342:3977817] client session: stateChange:0->,1 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:10.964 ThaliTest[1342:3977633] multipeer session: reset timer
,2016-04-28 21:29:10.964 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:10.964 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:11.026 ThaliTest[1342:3978386] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:11.026 ThaliTest[1342:3978386] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:11.0,27 ThaliTest[1342:3978386] client session: disconnect
2016-04-28 21:29:11.027 ThaliTest[1342:3978386] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:11.027 ThaliTest[1342:3978386] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:11.027 ThaliTest[1342:3978386] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:29:14.035 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:14.035 ThaliTest[1342:3977817] client session: connect
,2016-04-28 21:29:14.035 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:14.079 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:14.079 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:14.079 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:15.499 ThaliTest[1342:3978357] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:15.499 ThaliTest[1342:3978357] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:15.499 ThaliTest[1342:3978357] client session: disconnect
2016-04-28 21:29:15.499 ThaliTest[1342:3978357] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:15.499 ThaliTest[1342:3978357] client session: fireConnectCallb,ack: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:15.499 ThaliTest[1342:3978357] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-04-28 21:29:17.234 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:17.234 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:17.234 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:18.506 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:18.506 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:29:18.506 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:18.704 ThaliTest[1342:3978357] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:18.704 ThaliTest[1342:3978357] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:18.7,04 ThaliTest[1342:3978357] client session: disconnect
2016-04-28 21:29:18.705 ThaliTest[1342:3978357] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:18.705 ThaliTest[1342:3978357] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:18.705 ThaliTest[1342:3978357] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:29:19.560 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:19.560 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:29:19.560 ThaliTest[1342:3977633], server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:20.362 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:20.362 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:20.362 ThaliTest[1342:3977633], server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:21.712 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:21.713 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:29:21.713 ThaliTest[1342:3977817] client session: stateChange:0->,1 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:22.851 ThaliTest[1342:3978357] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:22.851 ThaliTest[1342:3978357] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:22.8,51 ThaliTest[1342:3978357] client session: disconnect
2016-04-28 21:29:22.851 ThaliTest[1342:3978357] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:22.851 ThaliTest[1342:3978357] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:22.851 ThaliTest[1342:3978357] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:29:23.508 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:23.508 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:23.509 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:25.859 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:25.859 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:29:25.859 ThaliTest[1342:3977817] client session: stateChange:0->,1 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:29:26.086 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:29:26.095 ThaliTest[1342:3977633] client: found updated peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:26.095 ThaliTest[1342:3977633] client: found updated peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:29:26.096 ThaliTest[1342:3977633] client: found updated peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"30403743-C17E-454C-8124-9D59A7B25203:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8","pleaseConnect":0}]
,2016-04-28 21:29:26.684 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:26.685 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:26.685 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:29.791 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:29.791 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:29.791 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:32.973 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:32.973 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:32.973 ThaliTest[1342:3977633], server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:32.976 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:32.976 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:29:32.976 ThaliTest[1342:3977633], server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:36.078 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:36.078 ThaliTest[1342:3977633] server: disconnecting to refresh session (C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF)
2016-04-28 21:29:36.078 ThaliTest[1342:3977633] server: rejecting invitation from C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:45.630 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:45.630 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:29:45.630 ThaliTest[1342:3977633], server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:46.086 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:29:46.092 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:46.093 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:46.093 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:29:58.416 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:29:58.417 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:29:58.417 ThaliTest[1342:3977633] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:29:58.850 ThaliTest[1342:3978574] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:58.850 ThaliTest[1342:3978574] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:58.850 ThaliTest[1342:3978574] client session: disconnect
2016-04-28 21:29:58.850 ThaliTest[1342:3978574] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:58.850 ThaliTest[1342:3978574] client session: fireConnectCallb,ack: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:29:58.850 ThaliTest[1342:3978574] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-28 21:30:01.859 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:30:01.859 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:30:01.860 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:02.912 ThaliTest[1342:3978573] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:02.912 ThaliTest[1342:3978573] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:02.912 ThaliTest[1342:3978573] client session: disconnect
2016-04-28 21:30:02.912 ThaliTest[1342:3978573] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:02.913 ThaliTest[1342:3978573] client session: fireConnectCallb,ack: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:02.913 ThaliTest[1342:3978573] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:30:05.925 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:30:05.926 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:30:05.926 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:06.086 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:30:06.095 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:30:06.095 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:06.095 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:11.514 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:30:11.514 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:30:11.514 ThaliTest[1342:3977633], server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:30:24.548 ThaliTest[1342:3977633] multipeer session: reset timer
,2016-04-28 21:30:24.548 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:30:24.548 ThaliTest[1342:3977633] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to p,revious generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:30:26.086 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:30:26.093 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:26.093 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:26.09,3 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:30:38.052 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:30:38.053 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:30:38.053 ThaliTest[1342:3977633] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:30:38.919 ThaliTest[1342:3978685] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:38.919 ThaliTest[1342:3978685] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:38.919 ThaliTest[1342:3978685] client session: disconnect
,2016-04-28 21:30:38.920 ThaliTest[1342:3978685] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:38.920 ThaliTest[1342:3978685] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:38.920 ThaliTest[1342:3978685] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:30:41.925 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:30:41.925 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:30:41.926 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:42.592 ThaliTest[1342:3978655] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:42.592 ThaliTest[1342:3978655] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:42.592 ThaliTest[1342:3978655] client session: disconnect
,2016-04-28 21:30:42.592 ThaliTest[1342:3978655] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:42.592 ThaliTest[1342:3978655] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:30:42.592 ThaliTest[1342:3978655] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:30:45.597 ThaliTest[1342:3977817] jxcore: connect 30403743-C17E-454C-8124-9D59A7B25203:7
,2016-04-28 21:30:45.598 ThaliTest[1342:3977817] client session: connect
2016-04-28 21:30:45.598 ThaliTest[1342:3977817] client session: stateChange:0->1 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:30:46.086 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:30:46.096 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:46.096 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:30:46.096 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:30:50.638 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:30:50.638 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:30:50.638 ThaliTest[1342:3977633] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:31:03.797 ThaliTest[1342:3977633] multipeer session: reset timer
2016-04-28 21:31:03.797 ThaliTest[1342:3977633] server: disconnecting to refresh session (337492EA-97B4-404F-B8FE-E0E7631E59C8)
2016-04-28 21:31:03.797 ThaliTest[1342:3977633] server: rejecting invitation from 337492EA-97B4-404F-B8FE-E0E7631E59C8 due to previous generation (418CC5DB-B63A-41DA-9996-4D5D4125B76C:8 != 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7)
,2016-04-28 21:31:06.086 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:31:06.094 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:31:06.094 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:06.094 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:18.560 ThaliTest[1342:3978763] client session: not connected 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:31:18.560 ThaliTest[1342:3978763] client session: onLinkFailure: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:31:18.5,60 ThaliTest[1342:3978763] client session: disconnect
2016-04-28 21:31:18.560 ThaliTest[1342:3978763] client session: stateChange:1->0 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:31:18.560 ThaliTest[1342:3978763] client session: fireConnectCallback: 30403743-C17E-454C-8124-9D59A7B25203
2016-04-28 21:31:18.560 ThaliTest[1342:3978763] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-04-28 21:31:18.676 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:31:18.677 ThaliTest[1342:3977817] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:31:18.678 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening
,2016-04-28 21:31:18.678 ThaliTest[1342:3977817] THEMultipeerManager stopping peer
,2016-04-28 21:31:18.678 ThaliTest[1342:3977817] multipeer manager: stop client timer
2016-04-28 21:31:18.679 ThaliTest[1342:3977817] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-28 21:31:20.565 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:31:20.565 ThaliTest[1342:3977817] server: starting 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:31:20.565 ThaliTest[1342:3977817] multipeer m,anager: start client restart timer: 0x15692220
2016-04-28 21:31:20.565 ThaliTest[1342:3977817] THEMultipeerManager initialized peer 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:31:20.565 ThaliTest[1342:3977817] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:31:20.566 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-28 21:31:20.566 ThaliTest[1342:3977817] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-28 21:31:20.910 ThaliTest[1342:3977633] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:20.910 ThaliTest[1342:3977633] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:20.911 ThaliTes,t[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:20.911 ThaliTest[1342:3977817] client: server will connect
2016-04-28 21:31:20.911 ThaliTest[1342:3977817] client session: reverseConnect
2016-04-28 21:31:20.911 ThaliTest[1342:3977817] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:22.598 ThaliTest[1342:3978764] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:22.598 ThaliTest[1342:3978764] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:22.598 ThaliTest[1342:3978764] client session: disconnect
,2016-04-28 21:31:22.598 ThaliTest[1342:3978764] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:22.599 ThaliTest[1342:3978764] client session: no connect callback (server initiated)
,2016-04-28 21:31:24.091 ThaliTest[1342:3977633] client: found new peer: 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:31:30.912 ThaliTest[1342:3977633] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:31:33.922 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:33.923 ThaliTest[1342:3977817] client: server will connect
2016-04-28 21:31:33.923 ThaliTest[1342:3977817] client session: reverseConn,ect
2016-04-28 21:31:33.923 ThaliTest[1342:3977817] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:34.172 ThaliTest[1342:3978822] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:34.173 ThaliTest[1342:3978822] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:34.173 ThaliTest[1342:3978822] client session: disconnect
,2016-04-28 21:31:34.173 ThaliTest[1342:3978822] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:34.173 ThaliTest[1342:3978822] client session: no connect callback (server initiated)
,2016-04-28 21:31:40.566 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:31:40.573 ThaliTest[1342:3977633] client: found updated peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:40.573 ThaliTest[1342:3977633] client: found updated peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:40.573 ThaliTest[1342:3977633] client: found updated peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:31:43.924 ThaliTest[1342:3977633] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:31:46.928 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:46.928 ThaliTest[1342:3977817] client: server will connect
,2016-04-28 21:31:46.928 ThaliTest[1342:3977817] client session: reverseConnect
,2016-04-28 21:31:46.929 ThaliTest[1342:3977817] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:47.233 ThaliTest[1342:3978822] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:47.233 ThaliTest[1342:3978822] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:31:47.234 ThaliTest[1342:3978822] client session: disconnect
2016-04-28 21:31:47.234 ThaliTest[1342:3978822] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:31:47.234 ThaliTest[1342:3978822] client session: no connect callback (server initiated)
,2016-04-28 21:31:56.930 ThaliTest[1342:3977633] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:31:59.932 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:59.933 ThaliTest[1342:3977817] client: server will connect
,2016-04-28 21:31:59.933 ThaliTest[1342:3977817] client session: reverseConnect
2016-04-28 21:31:59.933 ThaliTest[1342:3977817] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:00.565 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:32:00.575 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:00.575 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:32:00.576 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:09.934 ThaliTest[1342:3977633] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:32:12.936 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:12.936 ThaliTest[1342:3977817] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:12.936 ThaliTest[1342:3977817] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:32:15.946 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:15.946 ThaliTest[1342:3977817] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:15.946 Thali,Test[1342:3977817] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-28 21:32:18.955 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:32:18.955 ThaliTest[1342:3977817] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:18.955 ThaliTest[1342:3977817] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:32:20.566 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:32:20.574 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:20.574 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:20.576 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:32:21.965 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:32:21.966 ThaliTest[1342:3977817] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:21.966 ThaliTest[1342:3977817] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:32:24.972 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:24.973 ThaliTest[1342:3977817] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:32:24.973 ThaliTest[1342:3977817] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:32:27.987 ThaliTest[1342:3977817] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:32:27.988 ThaliTest[1342:3977817] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:27.988 ThaliTest[1342:3977817] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-28 21:32:32.879 ThaliTest[1342:3978933] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:32.879 ThaliTest[1342:3978933] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:32:32.880 ThaliTest[1342:3978933] client session: disconnect
2016-04-28 21:32:32.880 ThaliTest[1342:3978933] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:32.880 ThaliTest[1342:3978933] client session: no connect callback (server initiated)
,2016-04-28 21:32:40.566 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:32:40.574 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:40.575 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:40.575 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:00.566 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:33:00.574 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:33:00.574 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:33:00.575 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:33:20.566 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:33:20.575 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:33:20.575 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:33:20.575 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:33:40.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:33:40.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:33:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:34:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:34:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:34:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:34:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:34:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:34:20.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:34:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:34:40.562 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:40.562 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:34:40.562 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:35:00.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:35:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:35:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:35:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:35:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:35:20.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:35:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:35:40.551 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:35:40.559 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:35:40.559 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:35:40.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:36:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:36:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:36:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:36:20.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:36:20.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:36:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:36:40.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:40.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:36:40.562 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:37:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:37:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:37:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:37:20.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:37:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:37:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:37:40.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:40.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:37:40.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:38:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:38:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:38:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:38:00.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:38:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:38:20.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:38:20.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:38:20.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:38:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:38:40.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:38:40.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:38:40.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:39:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:39:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:39:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:39:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:39:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:39:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:39:20.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:39:20.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:39:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:39:40.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:39:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:39:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:40:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:00.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:40:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:40:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:40:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:40:20.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:40:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:40:40.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:40.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:40:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:41:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:41:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:41:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:41:00.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:41:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:41:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:41:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:41:20.56,0 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:41:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:41:40.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:41:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:41:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:42:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:42:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:42:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:42:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:42:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:42:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:42:20.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:42:20.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:42:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:42:40.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:42:40.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:42:40.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:43:00.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:00.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:43:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:43:20.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:43:20.562 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:20.562 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:43:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:43:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:43:40.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:44:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:44:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:44:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:20.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:44:20.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:44:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:44:40.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:44:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:45:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:45:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:45:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:45:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:45:20.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:45:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:45:40.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:45:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:46:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:46:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:46:00.563 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:46:20.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:46:20.560 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:46:20.560 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:46:20.560 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:46:40.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:46:40.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:46:40.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:46:40.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
,2016-04-28 21:47:00.552 ThaliTest[1342:3977633] multipeer manager: restart client
,2016-04-28 21:47:00.561 ThaliTest[1342:3977633] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:47:00.561 ThaliTest[1342:3977633] client: found existing peer: 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:47:00.561 ThaliTest[1342:3977633] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9

```
