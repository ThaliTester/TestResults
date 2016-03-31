#### Test 646138038b5bc7c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/20E57B9F-5B53-4299-AEE0-BF1A7E4FBC02/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/20E57B9F-5B53-4299-AEE0-BF1A7E4FBC02/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/646138038b5bc7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49910"
,(lldb)     command script import "/tmp/20E57B9F-5B53-4299-AEE0-BF1A7E4FBC02/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 17:38:22.848 ThaliTest[1954:4964555] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/52931C9C-5E20-48B2-BD28-05C162B62CFA/Library/Cookies/Cookies.binarycookies
,2016-03-31 17:38:22.948 ThaliTest[1954:4964555] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 17:38:22.950 ThaliTest[1954:4964555] Multi-tasking -> Device: YES, App: YES
,2016-03-31 17:38:22.968 ThaliTest[1954:4964555] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 17:38:24.090 ThaliTest[1954:4964555] Using UIWebView
,2016-03-31 17:38:24.094 ThaliTest[1954:4964555] [CDVTimer][handleopenurl] 0.289023ms
,2016-03-31 17:38:24.099 ThaliTest[1954:4964555] [CDVTimer][intentandnavigationfilter] 4.572988ms
2016-03-31 17:38:24.099 ThaliTest[1954:4964555] [CDVTimer][gesturehandler] 0.243008ms
2016-03-31 17:38:24.099 ThaliTest[1954:4964555] [CDVTimer][TotalPluginStartup] 5.998969ms
,2016-03-31 17:38:28.920 ThaliTest[1954:4964555] Resetting plugins due to page load.
,2016-03-31 17:38:31.257 ThaliTest[1954:4964555] Finished load of: file:///var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/index.html
,2016-03-31 17:38:31.445 ThaliTest[1954:4964555] JXcore Cordova plugin initializing
2016-03-31 17:38:31.448 ThaliTest[1954:4964692] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-31 17:38:45.564 ThaliTest[1954:4964692] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:38:45.565 ThaliTest[1954:4964692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:38:45.565 ThaliTest[1954:4,964692] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:38:45.568 ThaliTest[1954:4964692] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E02D9B2C-EFCC-4F77-B91C-79762345F969/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56481
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56483
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
DEBUG createNativeListener: listening 56486
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56490
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56495
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56499
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56503
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56507
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56511
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 56563
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56567
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
# teardown
,# setup
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. multiplex can send data
,ok 48 String should be length:200
,# teardown
,# setup
,# 17. enqueue and run in order
,ok 49 firstPromise setTimeout
ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
,ok 53 secondPromise result
,ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
ok 59 thirdPromise - in resolve
ok 60 secondPromise - second to run
ok 61 secondPromise - in catch
ok 62 firstPromise - third to run
ok 63 firstPromise - in then
ok 64 testing promises
# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
ok 67 second
ok 68 secondPromise - in then
,ok 69 first
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
# teardown
,# setup
,# 22. another
,ok 76 sane
# teardown
,# setup
,# 23. can pass data in setup
,[{"uuid":"93b06dd5-4156-4a62-b430-5e379b5bf668","data":"custom data"},{"uuid":"d360614e-eafc-47a4-b232-9db4049e83cd","data":"custom data"},{"uuid":"2d44cdcc-6331-4fd1-8321-40772b7965dd","data":"custom data"},{"uuid":"5a159754-f32d-49c6-9977-dc42c1fa4a99",",data":"custom data"}]
ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
,ok 83 test participant has uuid
ok 84 participant data matches
,ok 85 own UUID is found from the participants list
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 89 specific error should be returned
,# teardown
,ok 90 error should be null
ok 91 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56580
2016-03-31 17:41:32.810 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.811 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
2016-03-31 17:41:32.813 ThaliTest[1954:4964692] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.814 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
# teardown
,2016-03-31 17:41:32.946 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:32.947 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:32.947 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:32.947 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:32.948 ThaliTest[1954,:4964692] jxcore: stopListeningForAdvertisements: success
ok 96 error should be null
,ok 97 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56582
2016-03-31 17:41:33.305 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
,2016-03-31 17:41:33.307 ThaliTest[1954:4964692] multipeer manager: start client restart timer: 0x155b4d50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:33.308 Th,aliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
,ok 98 error should be null
ok 99 error should be null
2016-03-31 17:41:33.323 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-31 17:41:33.324 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 100 error should be null
ok 101 error should be null
# teardown
,2016-03-31 17:41:33.628 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:33.628 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:33.628 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:33.629 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
2016-03-31 17:41:33.629 ThaliTest[1954:4964692] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:33.630 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 102 error should be null
ok 103 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56584
,2016-03-31 17:41:34.228 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:34.228 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:1
2016-03-31 17:41:34.229 ThaliTest[1954:4964692] multipeer m,anager: start client restart timer: 0x155b4d50
2016-03-31 17:41:34.229 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:1
2016-03-31 17:41:34.229 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 104 error should be null
ok 105 error should be null
2016-03-31 17:41:34.242 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:34.242 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:34.242, ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:41:34.242 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:2
2016-03-31 17:41:34.243 ThaliTest[1954:4964692] multipeer manager: start client restart ,timer: 0x155b4d50
2016-03-31 17:41:34.243 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:2
2016-03-31 17:41:34.243 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening: success
,ok 106 error should be null
ok 107 error should be null
# teardown
,2016-03-31 17:41:35.373 ThaliTest[1954:4964555] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:2
,2016-03-31 17:41:35.497 ThaliTest[1954:4964555] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:2
,2016-03-31 17:41:37.187 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:37.187 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:37.188 ThaliTest[1954:4964692] multipeer manager: stop client timer
20,16-03-31 17:41:37.188 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:41:37.188 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:37.189 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 108 error should be null
,ok 109 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56589
2016-03-31 17:41:40.508 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.508 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:40.508 ThaliTest[1954:4964,692] jxcore: stopAdvertisingAndListening: success
ok 110 error should be null
ok 111 error should be null
,2016-03-31 17:41:40.511 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.511 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:40.511 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 112 error should be null
ok 113 error should be null
# teardown
,2016-03-31 17:41:40.806 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:40.806 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:40.807 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:40.807 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:40.808 ThaliTest[1954,:4964692] jxcore: stopListeningForAdvertisements: success
ok 114 error should be null
ok 115 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56591
,ok 116 first call should succeed
ok 117 first call should succeed
ok 118 specific error should be returned
,# teardown
,2016-03-31 17:41:42.976 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:42.976 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:42.977 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:42.977 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:42.978 ThaliTest[1954,:4964692] jxcore: stopListeningForAdvertisements: success
ok 119 error should be null
,ok 120 error should be null
,# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 56593
2016-03-31 17:41:56.286 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
2016-03-31 17:41:56.287 ThaliTest[1954:4964692] multipeer manager: start client restart timer: 0x155b4d50
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:41:56.287 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
,2016-03-31 17:41:56.307 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:41:56.307 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:3
2016-03-31 17:41:56.307 ThaliTest[1954:4964692] THEMultipee,rManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:3
2016-03-31 17:41:56.308 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening: success
,ok 121 called only once
,ok 122 discovery state matches
,ok 123 advertising state matches
,# teardown
,2016-03-31 17:41:56.488 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:41:56.488 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:41:56.488 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:41:56.489 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
2016-03-31 17:41:56.489 ThaliTest[1954:4964692] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:41:56.490 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 124 error should be null
ok 125 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 126 should be called once
ok 127 should not have been called more than once
,# teardown
,ok 128 error should be null
,ok 129 error should be null
# setup
,# 33. can get the network status
,ok 130 network status should have certain non-empty properties
# teardown
,ok 131 error should be null
ok 132 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 133 host address should match
ok 134 port should match
,ok 135 host address should be null
ok 136 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 137 error should be null
,ok 138 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 17:42:39.500 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
2016-03-31 17:42:39.502 ThaliTest[1954:4964692] multipeer manager: start client restart timer: 0x155b4d50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:39.503 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-31 17:42:39.504 ThaliTes,t[1954:4964692] jxcore: stopListeningForAdvertisements
2016-03-31 17:42:39.504 ThaliTest[1954:4964692] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-31 17:42:39.505 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 140 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 17:42:39.769 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:39.770 ThaliTest[1954:49646,92] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:42:39.771 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
,2016-03-31 17:42:39.772 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
,2016-03-31 17:42:39.772 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 17:42:42.867 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
2016-03-31 17:42:42.868 ThaliTest[1954:4964692] multipeer manager: start client restart timer: 0x155b4d50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:42.869 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements without error
2016-03-31 17:42:42.870 ThaliTes,t[1954:4964692] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:42:42.871 ThaliTest[1954:4964692] jxcore: startListeningForAdv,ertisements: success
ok 144 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 17:42:46.569 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
2016-03-31 17:42:46.569 ThaliTest[1954:4964692] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-31 17:42:46.570 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:46.571 ThaliTest[1954:49646,92] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:46.571 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:42:46.572 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 17:42:49.980 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:49.980 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:4
2016-03-31 17:42:49.981 ThaliTest[1954:4964692] multipeer m,anager: start client restart timer: 0x155b4d50
2016-03-31 17:42:49.981 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:4
2016-03-31 17:42:49.981 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:42:49.983 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:49.983 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016,-03-31 17:42:49.983 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:42:49.983 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 148 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-31 17:42:53.832 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:42:53.833 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:42:53.834 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:42:53.834 ThaliTest[1954:496469,2] THEMultipeerManager stopping peer
2016-03-31 17:42:53.834 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 17:42:57.764 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:57.764 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:5
2016-03-31 17:42:57.764 ThaliTest[1954:4964692] multipeer m,anager: start client restart timer: 0x155b4d50
2016-03-31 17:42:57.765 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:5
2016-03-31 17:42:57.765 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 151 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:42:57.766 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:42:57.766 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
,2016-03-31 17:42:57.766 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:42:57.772 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:6
2016-03-31 17:42:57.773 ThaliTest[1954:4964692] multipeer manager,: start client restart timer: 0x155b4d50
2016-03-31 17:42:57.773 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:6
2016-03-31 17:42:57.773 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 152 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 17:42:59.895 ThaliTest[1954:4964555] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:6
2016-03-31 17:42:59.896 ThaliTest[1954:4964555] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:6
,2016-03-31 17:43:00.872 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 17:43:00.873 ThaliTest[1954:496469,2] jxcore: stopListeningForAdvertisements: success
ok 153 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:43:00.874 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:43:00.874 ThaliTest[1954:4964692,] THEMultipeerManager stopping peer
2016-03-31 17:43:00.875 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:43:00.875 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 17:43:16.886 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:43:16.886 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:16.887 ThaliTest[1954:4964692] multipeer m,anager: start client restart timer: 0x155b4d50
2016-03-31 17:43:16.887 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7
2016-03-31 17:43:16.887 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 17:43:16.888 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-31 17:43:16.889 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:18.955 ThaliTest[1954:4964555] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
ok 157 peers must be an array
ok 158 peers must not be zero-length
2016-03-31 17:43:18.958 ThaliTest[1954:4964555] client: found new peer: E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
ok 159 peer must have peerIdentifier
ok 160 peerIdentifier must be a string
ok 161 peer must have peerAvailable
ok 162 peer must have pleaseConnect
,# teardown
,2016-03-31 17:43:19.405 ThaliTest[1954:4964555] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:7
,2016-03-31 17:43:20.472 ThaliTest[1954:4964555] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:21.120 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 17:43:21.122 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 17:43:21.124 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:43:21.124 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:43:21.124 ThaliTest[1954:4964692] multipeer manager: stop client timer
20,16-03-31 17:43:21.124 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-31 17:43:21.861 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:43:21.861 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:43:21.862 ThaliTest[1954:4964692] multipeer m,anager: start client restart timer: 0x155b4d50
2016-03-31 17:43:21.862 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8
2016-03-31 17:43:21.862 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:43:21.863 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 17:43:21.864 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-03-31 17:43:22.535 ThaliTest[1954:4964555] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2646853F-7FBE-4B67-A117-C1DAA2A4C,3FB:7","pleaseConnect":0}]
2016-03-31 17:43:22.537 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:22.538 ThaliTest[1954:4964692] client session: connect
,2016-03-31 17:43:22.538 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:22.774 ThaliTest[1954:4964555] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:7","pleaseConnect":0}]
,2016-03-31 17:43:22.950 ThaliTest[1954:4965266] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:22.950 ThaliTest[1954:4965266] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:22.9,50 ThaliTest[1954:4965266] client session: disconnect
2016-03-31 17:43:22.951 ThaliTest[1954:4965266] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:22.951 ThaliTest[1954:4965266] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:22.951 ThaliTest[1954:4965266] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-03-31 17:43:23.410 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:43:23.410 ThaliTest[1954:4964555] server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D,6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:43:24.600 ThaliTest[1954:4964555] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4F791D6C-3E6B-4315-830D-E0F106215081:8","pleaseConnect":0}]
,2016-03-31 17:43:25.959 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:25.960 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:25.960 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:26.237 ThaliTest[1954:4965288] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:26.237 ThaliTest[1954:4965288] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:26.237 ThaliTest[1954:4965288] client session: disconnect
,2016-03-31 17:43:26.237 ThaliTest[1954:4965288] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:26.239 ThaliTest[1954:4965288] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:26.240 ThaliTest[1954:4965288] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:43:29.249 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:29.249 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:29.250 ThaliTest[1954:4964692] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:29.342 ThaliTest[1954:4965288] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:29.345 ThaliTest[1954:4965288] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:29.3,45 ThaliTest[1954:4965288] client session: disconnect
2016-03-31 17:43:29.345 ThaliTest[1954:4965288] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:29.345 ThaliTest[1954:4965288] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:29.346 ThaliTest[1954:4965288] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-03-31 17:43:32.351 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:32.351 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:32.352 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:32.517 ThaliTest[1954:4965302] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:32.517 ThaliTest[1954:4965302] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:32.517 ThaliTest[1954:4965302] client session: disconnect
2016-03-31 17:43:32.517 ThaliTest[1954:4965302] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:32.520 ThaliTest[1954:4965302] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:32.520 ThaliTest[1954:4965302] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:43:35.524 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:35.525 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:35.525 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:35.659 ThaliTest[1954:4965302] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:35.663 ThaliTest[1954:4965302] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:35.663 ThaliTest[1954:4965302] client session: disconnect
2016-03-31 17:43:35.663 ThaliTest[1954:4965302] client session:, stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:35.664 ThaliTest[1954:4965302] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:35.664 ThaliTest[1954:4965302] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:43:36.187 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:43:36.187 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:43:36.188 ThaliTest[1954:4964555], server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:43:38.670 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:38.670 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:38.670 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:38.869 ThaliTest[1954:4965288] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:38.869 ThaliTest[1954:4965288] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:38.869 ThaliTest[1954:4965288] client session: disconnect
,2016-03-31 17:43:38.870 ThaliTest[1954:4965288] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:38.872 ThaliTest[1954:4965288] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:38.872 ThaliTest[1954:4965288] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:43:41.862 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:43:41.887 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:41.887 ThaliTest[1954:4964692] client session: connect
,2016-03-31 17:43:41.887 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
,2016-03-31 17:43:41.976 ThaliTest[1954:4964555] client: found updated peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8","pleaseConnect":0}]
,2016-03-31 17:43:42.002 ThaliTest[1954:4964555] client: found updated peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8","pleaseConnect":0}]
,2016-03-31 17:43:42.004 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:43:42.412 ThaliTest[1954:4965397] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:42.413 ThaliTest[1954:4965397] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:42.4,13 ThaliTest[1954:4965397] client session: disconnect
2016-03-31 17:43:42.414 ThaliTest[1954:4965397] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:42.414 ThaliTest[1954:4965397] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:42.414 ThaliTest[1954:4965397] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:43:45.428 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:45.428 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:45.428 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:45.746 ThaliTest[1954:4965264] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:45.748 ThaliTest[1954:4965264] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:45.7,48 ThaliTest[1954:4965264] client session: disconnect
2016-03-31 17:43:45.748 ThaliTest[1954:4965264] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:45.748 ThaliTest[1954:4965264] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:45.749 ThaliTest[1954:4965264] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:43:48.761 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:48.762 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:48.762 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:48.864 ThaliTest[1954:4964555] multipeer session: reset timer
,2016-03-31 17:43:48.865 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
,2016-03-31 17:43:48.865 ThaliTest[1954:4964555] server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:43:48.880 ThaliTest[1954:4965302] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:48.883 ThaliTest[1954:4965302] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:43:48.883 ThaliTest[1954:4965302] client session: disconnect
,2016-03-31 17:43:48.883 ThaliTest[1954:4965302] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:48.884 ThaliTest[1954:4965302] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:48.884 ThaliTest[1954:4965302] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 17:43:51.892 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:7
2016-03-31 17:43:51.892 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:43:51.893 ThaliTest[1954:4964692] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:51.986 ThaliTest[1954:4965319] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:43:51.987 ThaliTest[1954:4965319] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:51.9,87 ThaliTest[1954:4965319] client session: disconnect
2016-03-31 17:43:51.987 ThaliTest[1954:4965319] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:43:51.989 ThaliTest[1954:4965319] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:43:51.989 ThaliTest[1954:4965319] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 167 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-31 17:44:01.863 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:44:01.901 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:01.904 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:44:01.904 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:44:15.101 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:44:15.102 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:44:15.102 ThaliTest[1954:4964555], server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:44:21.863 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:44:21.887 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:44:21.888 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:44:21.893 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:28.071 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:44:28.071 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:44:28.071 ThaliTest[1954:4964555], server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:44:41.507 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:44:41.507 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:44:41.507 ThaliTest[1954:4964555], server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:44:41.863 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:44:41.887 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:44:41.888 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:44:41.88,8 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:44:54.724 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:44:54.724 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:44:54.724 ThaliTest[1954:4964555], server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:45:01.863 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:45:01.890 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:01.903 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
2016-03-31 17:45:01.906 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
,2016-03-31 17:45:07.466 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:45:07.466 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:45:07.466 ThaliTest[1954:4964555] server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:45:17.232 ThaliTest[1954:4964555] client: lost peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
2016-03-31 17:45:17.233 ThaliTest[1954:4964555] client session: onPeerLost: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498
,2016-03-31 17:45:18.796 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B9470F4B-F8C4-427A-8DC9-3B3E,0B52B498:8","pleaseConnect":0}]
,2016-03-31 17:45:20.032 ThaliTest[1954:4964555] multipeer session: reset timer
2016-03-31 17:45:20.033 ThaliTest[1954:4964555] server: disconnecting to refresh session (2646853F-7FBE-4B67-A117-C1DAA2A4C3FB)
2016-03-31 17:45:20.033 ThaliTest[1954:4964555], server: rejecting invitation from 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB due to previous generation (501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:8 != 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:7)
,2016-03-31 17:45:21.863 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:45:21.900 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:21.901 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:8
2016-03-31 17:45:21.902 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:31.185 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 17:45:31.186 ThaliTest[1954:496469,2] jxcore: stopListeningForAdvertisements: success
ok 168 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:45:31.187 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:45:31.187 ThaliTest[1954:4964692,] THEMultipeerManager stopping peer
2016-03-31 17:45:31.187 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:45:31.188 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
,ok 169 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. Can shift large amounts of data
,2016-03-31 17:45:34.966 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:45:34.966 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
2016-03-31 17:45:34.967 ThaliTest[1954:4964692] multipeer m,anager: start client restart timer: 0x155b4d50
2016-03-31 17:45:34.967 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:9
2016-03-31 17:45:34.967 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 170 Can call startUpdateAdvertisingAndListening without error
2016-03-31 17:45:34.969 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 17:45:34.970 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 171 Can call startListeningForAdvertisements without error
,2016-03-31 17:45:36.675 ThaliTest[1954:4964555] client: found new peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:36.676 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:36.676 ThaliTest[1954:4,964692] client session: connect
2016-03-31 17:45:36.676 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:36.680 ThaliTest[1954:4964555] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106,215081:8
2016-03-31 17:45:36.687 ThaliTest[1954:4964555] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:8
,2016-03-31 17:45:38.951 ThaliTest[1954:4965604] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:38.952 ThaliTest[1954:4965604] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:38.9,54 ThaliTest[1954:4965604] client session: disconnect
2016-03-31 17:45:38.954 ThaliTest[1954:4965604] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:38.954 ThaliTest[1954:4965604] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:38.954 ThaliTest[1954:4965604] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 17:45:41.963 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:41.963 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:45:41.963 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:43.880 ThaliTest[1954:4965604] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:43.882 ThaliTest[1954:4965604] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:43.8,82 ThaliTest[1954:4965604] client session: disconnect
2016-03-31 17:45:43.882 ThaliTest[1954:4965604] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:43.883 ThaliTest[1954:4965604] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:43.883 ThaliTest[1954:4965604] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 17:45:46.884 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:46.885 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:45:46.885 ThaliTest[1954:4964692] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:47.133 ThaliTest[1954:4965559] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:47.134 ThaliTest[1954:4965559] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:45:47.134 ThaliTest[1954:4965559] client session: disconnect
2016-03-31 17:45:47.135 ThaliTest[1954:4965559] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:47.136 ThaliTest[1954:4965559] client sess,ion: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:47.136 ThaliTest[1954:4965559] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: ,Scheduling a connect retry - retries left: 7
,2016-03-31 17:45:50.141 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:50.142 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:45:50.142 ThaliTest[1954:4964692] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:51.169 ThaliTest[1954:4965604] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:51.171 ThaliTest[1954:4965604] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:51.1,71 ThaliTest[1954:4965604] client session: disconnect
2016-03-31 17:45:51.171 ThaliTest[1954:4965604] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:51.171 ThaliTest[1954:4965604] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:51.171 ThaliTest[1954:4965604] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 17:45:54.179 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:54.179 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:45:54.179 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
,2016-03-31 17:45:54.608 ThaliTest[1954:4965620] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:54.608 ThaliTest[1954:4965620] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:54.608 ThaliTest[1954:4965620] client session: disconnect
2016-03-31 17:45:54.609 ThaliTest[1954:4965620] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:54.610 ThaliTest[1954:4965620] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:54.610 ThaliTest[1954:4965620] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 17:45:54.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:45:54.990 ThaliTest[1954:4964555] client: found updated peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:45:54.991 ThaliTest[1954:4964555] client: found updated peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:45:54.994 ThaliTest[1954:4964555] client: found updated peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:45:57.621 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:45:57.621 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:45:57.621 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:45:58.618 ThaliTest[1954:4965604] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:45:58.619 ThaliTest[1954:4965604] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:45:58.619 ThaliTest[1954:4965604] client session: disconnect
,2016-03-31 17:45:58.619 ThaliTest[1954:4965604] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:45:58.621 ThaliTest[1954:4965604] client session: fireConnectCallback: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
,2016-03-31 17:45:58.622 ThaliTest[1954:4965604] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-31 17:46:01.626 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:01.626 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:46:01.626 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:02.949 ThaliTest[1954:4965559] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:02.950 ThaliTest[1954:4965559] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:02.9,50 ThaliTest[1954:4965559] client session: disconnect
2016-03-31 17:46:02.950 ThaliTest[1954:4965559] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:02.951 ThaliTest[1954:4965559] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:02.951 ThaliTest[1954:4965559] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 17:46:05.953 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:05.953 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:46:05.953 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:06.974 ThaliTest[1954:4965636] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:06.975 ThaliTest[1954:4965636] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:06.9,75 ThaliTest[1954:4965636] client session: disconnect
2016-03-31 17:46:06.975 ThaliTest[1954:4965636] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:06.976 ThaliTest[1954:4965636] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:06.976 ThaliTest[1954:4965636] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 17:46:09.982 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:09.982 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:46:09.982 ThaliTest[1954:4964692] client session: stateChange:0->,1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:11.001 ThaliTest[1954:4965559] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:11.001 ThaliTest[1954:4965559] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:11.0,02 ThaliTest[1954:4965559] client session: disconnect
2016-03-31 17:46:11.003 ThaliTest[1954:4965559] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:11.003 ThaliTest[1954:4965559] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:11.003 ThaliTest[1954:4965559] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 1
,2016-03-31 17:46:14.007 ThaliTest[1954:4964692] jxcore: connect 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:8
2016-03-31 17:46:14.007 ThaliTest[1954:4964692] client session: connect
2016-03-31 17:46:14.007 ThaliTest[1954:4964692] client session: stateChange:0->1 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:14.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:46:14.990 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:46:15.005 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:15.006 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
,2016-03-31 17:46:34.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:46:35.007 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:35.009 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:35.00,9 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:46:47.009 ThaliTest[1954:4965670] client session: not connected 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:47.009 ThaliTest[1954:4965670] client session: onLinkFailure: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:47.0,09 ThaliTest[1954:4965670] client session: disconnect
2016-03-31 17:46:47.009 ThaliTest[1954:4965670] client session: stateChange:1->0 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:46:47.011 ThaliTest[1954:4965670] client session: fireConnectCallb,ack: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB
2016-03-31 17:46:47.011 ThaliTest[1954:4965670] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
not ok 172 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-03-31 17:46:54.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:46:54.997 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:46:54.997 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:46:54.997 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:14.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:47:15.004 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:15.005 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:15.007 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:34.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:47:35.004 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:35.005 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:35.00,6 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:47:54.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:47:54.997 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:47:54.997 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:47:54.99,7 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:14.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:48:14.997 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:14.998 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:14.998 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:34.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:48:34.998 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:34.999 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:34.999 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:48:54.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:48:54.995 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:48:54.996 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:48:54.997 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:49:14.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:49:15.000 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
2016-03-31 17:49:15.001 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:49:15.00,1 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
,2016-03-31 17:49:34.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:49:35.005 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:49:35.005 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:35.00,6 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:49:54.968 ThaliTest[1954:4964555] multipeer manager: restart client
,2016-03-31 17:49:54.996 ThaliTest[1954:4964555] client: found existing peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:9
2016-03-31 17:49:54.996 ThaliTest[1954:4964555] client: found existing peer: 4F791D6C-3E6B-4315-830D-E0F106215081:9
2016-03-31 17:49:54.99,7 ThaliTest[1954:4964555] client: found existing peer: 2646853F-7FBE-4B67-A117-C1DAA2A4C3FB:9
,2016-03-31 17:50:00.415 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 17:50:00.416 ThaliTest[1954:496469,2] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 17:50:00.417 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:00.417 ThaliTest[1954:4964692,] THEMultipeerManager stopping peer
2016-03-31 17:50:00.417 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:50:00.418 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,2016-03-31 17:50:11.213 ThaliTest[1954:4964692] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:11.214 ThaliTest[1954:4964692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:11.214 ThaliTest[1954:4,964692] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:50:11.215 ThaliTest[1954:4964692] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 42. #startListeningForAdvertisements should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
# setup
,2016-03-31 17:50:23.733 ThaliTest[1954:4964692] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:23.734 ThaliTest[1954:4964692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:23.734 ThaliTest[1954:4,964692] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:23.736 ThaliTest[1954:4964692] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 177 specific error should be returned
# teardown
,ok 178 must be stopped
,# setup
,2016-03-31 17:50:25.197 ThaliTest[1954:4964692] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:25.198 ThaliTest[1954:4964692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:25.198 ThaliTest[1954:4,964692] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:25.200 ThaliTest[1954:4964692] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56630
2016-03-31 17:50:25.399 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:50:25.400 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 179 no errors
2016-03-31 17:50:25.402 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:50:25.402 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 180 still no errors
,# teardown
,2016-03-31 17:50:26.259 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:50:26.259 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:50:26.259 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:50:26.260 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 17:50:26.260 ThaliTest[1954,:4964692] jxcore: stopListeningForAdvertisements: success
ok 181 must be stopped
# setup
,2016-03-31 17:50:33.290 ThaliTest[1954:4964692] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:50:33.290 ThaliTest[1954:4964692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:50:33.290 ThaliTest[1954:4,964692] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 17:50:33.292 ThaliTest[1954:4964692] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56632
,2016-03-31 17:50:56.845 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
2016-03-31 17:50:56.845 ThaliTest[1954:4964692] multipeer manager: start client restart timer: 0x155b4d50
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:50:56.849 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements: success
ok 182 no errors
2016-03-31 17:50:,56.850 ThaliTest[1954:4964692] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 17:50:56.851 ThaliTest[1954:4964692] jxcore: start,ListeningForAdvertisements: success
ok 183 still no errors
# teardown
,2016-03-31 17:51:14.083 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:51:14.083 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:51:14.083 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 17:51:14.084 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
2016-03-31 17:51:14.084 ThaliTest[1954:4964692] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:51:14.085 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
ok 184 must be stopped
,# setup
,2016-03-31 17:51:19.799 ThaliTest[1954:4964692] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 17:51:19.800 ThaliTest[1954:4964692] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 17:51:19.800 ThaliTest[1954:4,964692] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 17:51:19.801 ThaliTest[1954:4964692] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 56634
2016-03-31 17:51:22.281 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:22.281 ThaliTest[1954:4964692] server: starting 50,1F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:10
2016-03-31 17:51:22.281 ThaliTest[1954:4964692] multipeer manager: start client restart timer: 0x155b4d50
2016-03-31 17:51:22.282 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-6,1B1D6196FBA:10
2016-03-31 17:51:22.282 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening: success
ok 185 no errors
2016-03-31 17:51:22.283 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListening
2016-03-31 17:51:22.283 Thali,Test[1954:4964692] THEMultipeerManager stopping peer
,2016-03-31 17:51:22.284 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:51:22.289 ThaliTest[1954:4964692] server: starting 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:11
2016-03-31 17:51:22.289 ThaliTest[1954:4964692] multipeer manage,r: start client restart timer: 0x155b4d50
2016-03-31 17:51:22.289 ThaliTest[1954:4964692] THEMultipeerManager initialized peer 501F3ADB-B1BD-4ACF-9A35-61B1D6196FBA:11
2016-03-31 17:51:22.290 ThaliTest[1954:4964692] jxcore: startUpdateAdvertisingAndListen,ing: success
ok 186 still no errors
# teardown
,2016-03-31 17:51:27.615 ThaliTest[1954:4964555] client: found new peer: 4F791D6C-3E6B-4315-830D-E0F106215081:11
,2016-03-31 17:51:30.277 ThaliTest[1954:4964555] client: found new peer: B9470F4B-F8C4-427A-8DC9-3B3E0B52B498:11
,2016-03-31 17:51:30.318 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening
2016-03-31 17:51:30.318 ThaliTest[1954:4964692] THEMultipeerManager stopping peer
2016-03-31 17:51:30.319 ThaliTest[1954:4964692] multipeer manager: stop client timer
2016-03-31 17:51:30.319 ThaliTest[1954:4964692] jxcore: stopAdvertisingAndListening: success
2016-03-31 17:51:30.319 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 17:51:30.320 ThaliTest[1954:4964692] jxcore: stopListeningForAdvertisements: success
,ok 187 must be stopped
,# setup

```
