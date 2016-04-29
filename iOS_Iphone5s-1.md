#### Test 68102130f73255a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/620F57A5-1059-4A48-B49D-F258A853194B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/620F57A5-1059-4A48-B49D-F258A853194B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55217"
,(lldb)     command script import "/tmp/620F57A5-1059-4A48-B49D-F258A853194B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-29 10:09:44.342 ThaliTest[3845:8997042] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/26704822-9497-4A9C-9C5F-D45DEE3A929C/Library/Cookies/Cookies.binarycookies
,2016-04-29 10:09:44.753 ThaliTest[3845:8997042] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-29 10:09:44.755 ThaliTest[3845:8997042] Multi-tasking -> Device: YES, App: YES
,2016-04-29 10:09:44.777 ThaliTest[3845:8997042] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-29 10:09:46.834 ThaliTest[3845:8997042] Using UIWebView
,2016-04-29 10:09:46.841 ThaliTest[3845:8997042] [CDVTimer][handleopenurl] 0.665963ms
,2016-04-29 10:09:46.850 ThaliTest[3845:8997042] [CDVTimer][intentandnavigationfilter] 8.028984ms
2016-04-29 10:09:46.851 ThaliTest[3845:8997042] [CDVTimer][gesturehandler] 0.431955ms
2016-04-29 10:09:46.851 ThaliTest[3845:8997042] [CDVTimer][TotalPluginStartup] 10.954976ms
,2016-04-29 10:09:53.864 ThaliTest[3845:8997042] Resetting plugins due to page load.
,2016-04-29 10:09:57.540 ThaliTest[3845:8997042] Finished load of: file:///var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/index.html
,2016-04-29 10:09:57.785 ThaliTest[3845:8997042] JXcore Cordova plugin initializing
,2016-04-29 10:09:57.786 ThaliTest[3845:8997284] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-29 10:10:06.576 ThaliTest[3845:8997284] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-29 10:10:06.576 ThaliTest[3845:8997284] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-29 10:10:06.576 ThaliTest[3845:8,997284] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-29 10:10:06.579 ThaliTest[3845:8997284] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/10DCE43F-9E9D-41F7-8B72-9D3F1FA991F3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-29 10:10:13.607 ThaliTest[3845:8997042] THREAD WARNING: ['JXcore'] took '6666.248047' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65426
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65428
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
,DEBUG createNativeListener: listening 65431
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
,DEBUG createNativeListener: listening 65435
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
,DEBUG createNativeListener: listening 65440
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
,DEBUG createNativeListener: listening 65444
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
,DEBUG createNativeListener: listening 65448
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
,DEBUG createNativeListener: listening 65452
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
,DEBUG createNativeListener: listening 65456
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
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
ok 29 native server should be closed
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
,DEBUG createNativeListener: listening 65508
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
,DEBUG createNativeListener: listening 65512
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
,[{"uuid":"831652d1-f5dc-4370-9bb4-e736119d075f","data":"custom data"},{"uuid":"b7ccdf89-53fb-4b69-acec-42a4f66f335f","data":"custom data"},{"uuid":"b7cd0fef-ad33-49c5-8781-858c9a5e3542","data":"custom data"},{"uuid":"f94a4309-984a-4df8-a677-f820db7183f0",",data":"custom data"}]
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
,DEBUG createNativeListener: listening 65522
,2016-04-29 10:12:44.048 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.049 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-29 10:12:44.051 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:44.052 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-29 10:12:44.246 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:44.247 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:12:44.247 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:12:44.247 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:44.248 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65524
,2016-04-29 10:12:44.604 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
,2016-04-29 10:12:44.608 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:12:44.611 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-29 10:12:44.763 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:12:44.766 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-29 10:12:44.961 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:44.962 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:12:44.962 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:12:44.963 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,2016-04-29 10:12:44.965 ThaliTest[3845:8997284] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:44.968 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65526
,2016-04-29 10:12:45.510 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:12:45.512 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:1
2016-04-29 10:12:45.514 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
2016-04-29 10:12:45.514 ThaliTest[3845:89972,84] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:1
2016-04-29 10:12:45.514 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-29 10:12:45.544 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:12:45.545 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:12:45.546 ThaliTest[3845:8997284] multipeer manager: stop client ti,mer
2016-04-29 10:12:45.547 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:2
2016-04-29 10:12:45.548 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
2016-04-29 10:12:45.549 ThaliTest[3845:,8997284] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:2
2016-04-29 10:12:45.549 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-29 10:12:46.724 ThaliTest[3845:8997042] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:2
,2016-04-29 10:12:47.407 ThaliTest[3845:8997042] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:2
,2016-04-29 10:12:49.021 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
,2016-04-29 10:12:49.021 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:12:49.023 ThaliTest[3845:8997284] multipeer manager: stop client timer
2016-04-29 10:12:49.023 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: su,ccess
2016-04-29 10:12:49.024 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:49.026 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65531
,2016-04-29 10:13:03.707 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.707 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:03.708 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-29 10:13:03.714 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.714 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:03.715 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-29 10:13:03.836 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:03.836 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:03.837 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
,2016-04-29 10:13:03.837 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:03.841 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65533
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-29 10:13:04.336 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:04.337 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:04.337 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:04.338 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:04.342 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65535
,2016-04-29 10:13:04.682 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
,2016-04-29 10:13:04.684 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:04.686 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,2016-04-29 10:13:04.715 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:04.716 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:3
2016-04-29 10:13:04.717 ThaliTest[3845:8997284] THEMultipee,rManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:3
2016-04-29 10:13:04.717 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-29 10:13:04.816 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
,2016-04-29 10:13:04.816 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:04.818 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:13:04.819 ThaliTest[3845:8997284] jxcore: stopListeningForAdverti,sements
2016-04-29 10:13:04.819 ThaliTest[3845:8997284] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:04.821 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,2016-04-29 10:13:28.560 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
2016-04-29 10:13:28.561 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:28.563 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-29 10:13:28.568 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:28.568 ThaliTest[3845:8997284] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-29 10:13:28.573 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:28.828 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:28.831 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:28.835 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:28.835 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:28.836 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-29 10:13:29.394 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
2016-04-29 10:13:29.395 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:13:29.398 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
2016-04-29 10:13:29.403 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"disco,veryActive":true}
2016-04-29 10:13:29.405 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-29 10:13:29.570 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:29.571 ThaliTest[3845:8997284] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:29.573 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-29 10:13:29.579 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:29.580 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:,13:29.581 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-29 10:13:32.420 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:32.423 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-29 10:13:32.426 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:32.429 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:46.495 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:46.498 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:46.502 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:46.502 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:46.503 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-29 10:13:47.045 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.046 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:4
2016-04-29 10:13:47.047 ThaliTest[3845:8997284] multipeer m,anager: start client restart timer: 0x17d502a0
2016-04-29 10:13:47.048 ThaliTest[3845:8997284] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:4
2016-04-29 10:13:47.048 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:13:47.052 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:47.053 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:47.053 ThaliTest[3845:8997284] multipeer manager: stop client timer
20,16-04-29 10:13:47.054 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:13:47.362 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:47.365 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:47.369 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
,2016-04-29 10:13:47.371 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
,2016-04-29 10:13:47.372 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-29 10:13:47.850 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.851 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:5
2016-04-29 10:13:47.852 ThaliTest[3845:8997284] multipeer m,anager: start client restart timer: 0x17d502a0
2016-04-29 10:13:47.852 ThaliTest[3845:8997284] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:5
2016-04-29 10:13:47.853 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:47.856 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:47.856 ThaliTest[3845:8997284] THEMultipeerManager stopping pee,r
2016-04-29 10:13:47.857 ThaliTest[3845:8997284] multipeer manager: stop client timer
2016-04-29 10:13:47.857 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:6
2016-04-29 10:13:47.858 ThaliTest[3845:8997284] multipeer mana,ger: start client restart timer: 0x17d502a0
2016-04-29 10:13:47.866 ThaliTest[3845:8997284] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:6
2016-04-29 10:13:47.866 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListe,ning: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-29 10:13:47.886 ThaliTest[3845:8997042] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:2
,2016-04-29 10:13:48.013 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:13:48.015 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:48.019 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:48.020 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:48.020 ThaliTest[3845:8997284] multipeer manager: stop client timer
20,16-04-29 10:13:48.021 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-29 10:13:53.969 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:53.970 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:53.970 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:13:53.974 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:53.974 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:13:53.974 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:14:05.181 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:05.184 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:05.187 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:05.188 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:14:05.188 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: suc,cess
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-29 10:14:08.397 ThaliTest[3845:8997284] jxcore: connect foo
2016-04-29 10:14:08.397 ThaliTest[3845:8997284] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-29 10:14:08.601 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:08.603 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:08.608 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:08.608 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:14:08.608 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-29 10:14:08.935 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:08.935 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:7
2016-04-29 10:14:08.936 ThaliTest[3845:8997284] multipeer m,anager: start client restart timer: 0x17d502a0
2016-04-29 10:14:08.937 ThaliTest[3845:8997284] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:7
2016-04-29 10:14:08.937 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-29 10:14:08.941 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-29 10:14:08.945 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:09.719 ThaliTest[3845:8997042] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:2
,ok 167 peers must be an array
ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-29 10:14:10.948 ThaliTest[3845:8997042] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:10.948 ThaliTest[3845:8997042] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
,2016-04-29 10:14:12.611 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:14:12.613 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:12.617 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:12.617 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:14:12.618 ThaliTest[3845:8997284] multipeer manager: stop client timer
20,16-04-29 10:14:12.618 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-29 10:14:41.643 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:41.644 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:14:41.645 ThaliTest[3845:8997284] multipeer m,anager: start client restart timer: 0x17d502a0
2016-04-29 10:14:41.646 ThaliTest[3845:8997284] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:14:41.646 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:14:41.649 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
,2016-04-29 10:14:41.651 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements: success
,ok 176 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:41.684 ThaliTest[3845:8997042] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:41.685 ThaliTest[3845:8997042] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8","pleaseConnect":0}]
,2016-04-29 10:14:41.700 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:41.702 ThaliTest[3845:8997284] client: server will connect
,2016-04-29 10:14:41.705 ThaliTest[3845:8997284] client session: reverseConnect
,2016-04-29 10:14:41.707 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EF331042-C426-4B67-BF95-35460DC67D54:8","pleaseConnect":0}]
,2016-04-29 10:14:43.787 ThaliTest[3845:8997042] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A45,2F4:7","pleaseConnect":0}]
,2016-04-29 10:14:51.706 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:14:54.496 ThaliTest[3845:8999244] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:54.496 ThaliTest[3845:8999244] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:14:54.497 ThaliTest[3845:8999244] client session: disconnect
2016-04-29 10:14:54.498 ThaliTest[3845:8999244] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:54.499 ThaliTest[3845:8999244] client session: no connect callback (server initiated)
,2016-04-29 10:14:54.719 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:54.719 ThaliTest[3845:8997284] client: server will connect
,2016-04-29 10:14:54.720 ThaliTest[3845:8997284] client session: reverseConnect
2016-04-29 10:14:54.720 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:55.439 ThaliTest[3845:8999244] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:55.442 ThaliTest[3845:8999244] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:55.442 ThaliTest[3845:8999244] client session: disconnect
2016-04-29 10:14:55.443 ThaliTest[3845:8999244] client session:, stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:55.443 ThaliTest[3845:8999244] client session: no connect callback (server initiated)
,2016-04-29 10:15:01.647 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:15:01.689 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:01.690 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:01.69,3 ThaliTest[3845:8997042] client: found updated peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":0}]
,2016-04-29 10:15:04.721 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:15:07.730 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:07.731 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:15:07.731 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:15:07.732 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:09.020 ThaliTest[3845:8999284] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:09.020 ThaliTest[3845:8999284] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:15:09.0,21 ThaliTest[3845:8999284] client session: disconnect
2016-04-29 10:15:09.021 ThaliTest[3845:8999284] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:09.024 ThaliTest[3845:8999284] client session: no connect callback (server initiated)
,2016-04-29 10:15:17.732 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:15:20.748 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:20.749 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:15:20.750 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:15:20.750 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:21.538 ThaliTest[3845:8999284] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:21.539 ThaliTest[3845:8999284] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:15:21.540 ThaliTest[3845:8999284] client session: disconnect
2016-04-29 10:15:21.542 ThaliTest[3845:8999284] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:21.544 ThaliTest[3845:8999284] client session: no connect callback (server initiated)
,2016-04-29 10:15:21.647 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:15:21.691 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:21.692 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:21.69,6 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:15:30.751 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:15:33.766 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:33.767 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:15:33.767 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:15:33.768 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:34.604 ThaliTest[3845:8999389] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:34.605 ThaliTest[3845:8999389] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:15:34.608 ThaliTest[3845:8999389] client session: disconnect
2016-04-29 10:15:34.608 ThaliTest[3845:8999389] client session:, stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:34.609 ThaliTest[3845:8999389] client session: no connect callback (server initiated)
,2016-04-29 10:15:41.646 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:15:41.698 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:15:41.699 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:15:41.70,0 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:43.769 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:15:46.779 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:46.780 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:15:46.780 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:15:46.781 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:48.711 ThaliTest[3845:8999432] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:48.713 ThaliTest[3845:8999432] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:15:48.7,13 ThaliTest[3845:8999432] client session: disconnect
2016-04-29 10:15:48.713 ThaliTest[3845:8999432] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:48.714 ThaliTest[3845:8999432] client session: no connect callb,ack (server initiated)
,2016-04-29 10:15:56.781 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:15:59.790 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:59.791 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:15:59.792 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:15:59.792 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:01.647 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:16:01.703 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:16:01.704 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:01.715 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:09.793 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:16:12.801 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:12.802 ThaliTest[3845:8997284] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:12.802 Thali,Test[3845:8997284] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:16:15.821 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:15.822 ThaliTest[3845:8997284] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:15.822 Thali,Test[3845:8997284] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:16:18.839 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:18.840 ThaliTest[3845:8997284] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:18.840 Thali,Test[3845:8997284] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-04-29 10:16:21.647 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:16:21.698 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:21.699 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:21.706 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:32.792 ThaliTest[3845:8999513] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:32.792 ThaliTest[3845:8999513] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:32.7,92 ThaliTest[3845:8999513] client session: disconnect
2016-04-29 10:16:32.793 ThaliTest[3845:8999513] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:32.794 ThaliTest[3845:8999513] client session: no connect callback (server initiated)
,2016-04-29 10:16:41.647 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:16:41.960 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:16:41.961 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:41.969 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:42.074 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-29 10:16:42.077 ThaliTest[3845:8997284] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:16:42.080 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening
2016-04-29 10:16:42.081 ThaliTest[3845:8997284] THEMultipeerManager stopping peer
2016-04-29 10:16:42.082 ThaliTest[3845:8997284] multipeer manager: stop client timer
20,16-04-29 10:16:42.082 ThaliTest[3845:8997284] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-29 10:16:42.998 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:16:42.999 ThaliTest[3845:8997284] server: starting DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:16:43.002 ThaliTest[3845:8997284] multipeer manager: start client restart timer: 0x17d502a0
2016-04-29 10:16:43.002 ThaliTest[3845:89972,84] THEMultipeerManager initialized peer DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:16:43.002 ThaliTest[3845:8997284] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-,29 10:16:43.006 ThaliTest[3845:8997284] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:16:43.007 ThaliTest[3845:8997284] jxcor,e: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-29 10:16:44.116 ThaliTest[3845:8997042] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:44.117 ThaliTest[3845:8997042] client: found new peer: EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:16:44.124 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:44.126 ThaliTest[3845:8997284] client: server will connect
,2016-04-29 10:16:44.127 ThaliTest[3845:8997284] client session: reverseConnect
,2016-04-29 10:16:44.128 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:45.383 ThaliTest[3845:8997042] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:46.154 ThaliTest[3845:8999514] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:46.155 ThaliTest[3845:8999514] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:46.1,55 ThaliTest[3845:8999514] client session: disconnect
2016-04-29 10:16:46.157 ThaliTest[3845:8999514] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:46.158 ThaliTest[3845:8999514] client session: no connect callb,ack (server initiated)
,2016-04-29 10:16:54.129 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:16:57.135 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:57.136 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:16:57.137 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:16:57.137 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:57.789 ThaliTest[3845:8999514] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:57.789 ThaliTest[3845:8999514] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:57.7,90 ThaliTest[3845:8999514] client session: disconnect
,2016-04-29 10:16:57.792 ThaliTest[3845:8999514] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:57.796 ThaliTest[3845:8999514] client session: no connect callback (server initiated)
,2016-04-29 10:17:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:17:03.045 ThaliTest[3845:8997042] client: found updated peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:03.046 ThaliTest[3845:8997042] client: found updated peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:17:03.057 ThaliTest[3845:8997042] client: found updated peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:07.138 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:17:10.146 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:10.147 ThaliTest[3845:8997284] client: server will connect
,2016-04-29 10:17:10.148 ThaliTest[3845:8997284] client session: reverseConnect
2016-04-29 10:17:10.149 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:12.207 ThaliTest[3845:8999587] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:12.208 ThaliTest[3845:8999587] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:12.2,09 ThaliTest[3845:8999587] client session: disconnect
2016-04-29 10:17:12.209 ThaliTest[3845:8999587] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:12.210 ThaliTest[3845:8999587] client session: no connect callb,ack (server initiated)
,2016-04-29 10:17:20.149 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:17:23.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:17:23.040 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:23.041 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:23.04,5 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:23.155 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:23.156 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:17:23.156 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:17:23.157 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:24.926 ThaliTest[3845:8999595] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:24.926 ThaliTest[3845:8999595] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:17:24.926 ThaliTest[3845:8999595] client session: disconnect
,2016-04-29 10:17:24.928 ThaliTest[3845:8999595] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:24.931 ThaliTest[3845:8999595] client session: no connect callback (server initiated)
,2016-04-29 10:17:33.158 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:17:36.173 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:36.174 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:17:36.174 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:17:36.175 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:37.160 ThaliTest[3845:8999668] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:37.161 ThaliTest[3845:8999668] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:37.162 ThaliTest[3845:8999668] client session: disconnect
,2016-04-29 10:17:37.162 ThaliTest[3845:8999668] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:37.167 ThaliTest[3845:8999668] client session: no connect callback (server initiated)
,2016-04-29 10:17:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:17:43.054 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:17:43.056 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:43.06,5 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:46.176 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:17:49.183 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:49.184 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:17:49.184 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:17:49.185 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:50.607 ThaliTest[3845:8999704] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:50.609 ThaliTest[3845:8999704] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:50.6,09 ThaliTest[3845:8999704] client session: disconnect
2016-04-29 10:17:50.610 ThaliTest[3845:8999704] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:50.610 ThaliTest[3845:8999704] client session: no connect callb,ack (server initiated)
,2016-04-29 10:17:59.185 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:18:02.194 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:02.194 ThaliTest[3845:8997284] client: server will connect
2016-04-29 10:18:02.195 ThaliTest[3845:8997284] client session: reverseConn,ect
2016-04-29 10:18:02.195 ThaliTest[3845:8997284] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:18:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:18:03.059 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:03.060 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:03.063 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:18:12.195 ThaliTest[3845:8997042] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:18:15.209 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:15.210 ThaliTest[3845:8997284] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:15.210 Thali,Test[3845:8997284] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:18:18.224 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:18.225 ThaliTest[3845:8997284] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:18:18.225 Thali,Test[3845:8997284] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:18:21.235 ThaliTest[3845:8997284] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:18:21.236 ThaliTest[3845:8997284] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:18:21.237 ThaliTest[3845:8997284] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-29 10:18:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:18:23.056 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:23.057 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:23.060 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:18:35.206 ThaliTest[3845:8999786] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:35.207 ThaliTest[3845:8999786] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:18:35.2,07 ThaliTest[3845:8999786] client session: disconnect
2016-04-29 10:18:35.207 ThaliTest[3845:8999786] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:35.208 ThaliTest[3845:8999786] client session: no connect callb,ack (server initiated)
,2016-04-29 10:18:43.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:18:43.056 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:43.060 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:18:43.06,0 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:19:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:19:03.058 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:19:03.059 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:19:03.069 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:19:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:19:23.059 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:19:23.059 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:19:23.06,0 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:19:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:19:43.057 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:19:43.058 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:19:43.06,2 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:03.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:20:03.057 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:20:03.058 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:20:03.05,8 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:20:23.047 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:20:23.048 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:20:23.049 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:20:43.055 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:20:43.056 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:20:43.05,6 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:21:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:21:03.052 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:21:03.057 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:21:03.058 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:21:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:21:23.048 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:21:23.049 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:21:23.05,3 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:21:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:21:43.053 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:21:43.057 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:21:43.05,7 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:22:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:22:03.055 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:22:03.056 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:22:03.059 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:22:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:22:23.056 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:22:23.057 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:22:23.069 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:22:43.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:22:43.058 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:22:43.059 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:22:43.06,0 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:23:03.050 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:23:03.051 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:23:03.058 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:23:23.056 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:23:23.058 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:23:23.066 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:43.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:23:43.056 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:23:43.061 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:43.062 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:24:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:24:03.059 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:24:03.062 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:03.063 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:24:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:24:23.057 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:24:23.058 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:23.06,2 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:24:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:24:43.054 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:24:43.055 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:24:43.05,5 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:25:03.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:25:03.056 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:25:03.056 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:25:03.05,7 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:25:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:25:23.054 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:25:23.057 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:25:23.058 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:25:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:25:43.061 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:25:43.062 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:25:43.063 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:26:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:26:03.059 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:26:03.059 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:26:03.06,2 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:26:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:26:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:26:43.033 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:26:43.034 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:26:43.036 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:27:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:27:03.037 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:03.039 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:27:03.04,0 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:27:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:27:23.038 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:23.039 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:27:23.039 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:27:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:27:43.038 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:43.039 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:27:43.03,9 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:28:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:28:03.040 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:28:03.040 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:28:03.04,1 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:28:23.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:28:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:28:43.034 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:28:43.035 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:28:43.03,6 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:29:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:29:03.035 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:29:03.040 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:29:03.042 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:29:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:29:23.037 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:29:23.037 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:29:23.038 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:29:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:29:43.038 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:29:43.038 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:29:43.039 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:30:03.003 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:30:03.034 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:30:03.035 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:30:03.041 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:30:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:30:23.035 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:30:23.037 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:23.039 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:30:43.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:30:43.037 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:30:43.038 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:43.038 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:31:03.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:31:03.037 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:31:03.038 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:31:03.038 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:31:23.004 ThaliTest[3845:8997042] multipeer manager: restart client
,2016-04-29 10:31:23.038 ThaliTest[3845:8997042] client: found existing peer: EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:31:23.039 ThaliTest[3845:8997042] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:31:23.040 ThaliTest[3845:8997042] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9

```
