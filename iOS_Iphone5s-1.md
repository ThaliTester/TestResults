#### Test 656816764cf5745_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/1C588B3F-2759-47C2-8B43-E0509A01FC9F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1C588B3F-2759-47C2-8B43-E0509A01FC9F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51798"
,(lldb)     command script import "/tmp/1C588B3F-2759-47C2-8B43-E0509A01FC9F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:22:56.149 ThaliTest[2971:5766685] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B62F4224-4222-40DF-8BE0-DBDF77237566/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:22:56.412 ThaliTest[2971:5766685] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:22:56.413 ThaliTest[2971:5766685] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:22:56.430 ThaliTest[2971:5766685] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:22:57.244 ThaliTest[2971:5766685] Using UIWebView
2016-04-07 21:22:57.247 ThaliTest[2971:5766685] [CDVTimer][handleopenurl] 0.160038ms
,2016-04-07 21:22:57.249 ThaliTest[2971:5766685] [CDVTimer][intentandnavigationfilter] 2.635002ms
2016-04-07 21:22:57.250 ThaliTest[2971:5766685] [CDVTimer][gesturehandler] 0.165045ms
,2016-04-07 21:22:57.250 ThaliTest[2971:5766685] [CDVTimer][TotalPluginStartup] 3.670990ms
,2016-04-07 21:23:00.410 ThaliTest[2971:5766685] Resetting plugins due to page load.
,2016-04-07 21:23:01.868 ThaliTest[2971:5766685] Finished load of: file:///var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/index.html
,2016-04-07 21:23:02.056 ThaliTest[2971:5766685] JXcore Cordova plugin initializing
,2016-04-07 21:23:02.058 ThaliTest[2971:5766834] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:23:10.483 ThaliTest[2971:5766834] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-07 21:23:10.485 ThaliTest[2971:5766834] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-07 21:23:10.485 ThaliTest[2971:5766834] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-07 21:23:10.488 ThaliTest[2971:5766834] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/34F1F617-680B-476E-B4E4-732C5074ADD6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60331
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60333
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60336
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 60340
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
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
DEBUG createNativeListener: listening 60345
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60349
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60353
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60357
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60361
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createN,ativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new ,mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 60413
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
,ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60417
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
ok 63 testing promises
# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
,ok 64 fourth
ok 65 fourth
ok 66 second
ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 20. basic
,ok 74 sane
# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"03445e62-5e92-48cc-8875-30b0fdcb1b59","data":"custom data"},{"uuid":"cc977dc9-3774-4da7-8114-07bc6d4a1955","data":"custom data"},{"uuid":"856d22a5-0926-412e-b7a9-ad2877c2c912","data":"custom data"},{"uuid":"1019d4f9-108b-42a3-b511-e8f2013d3ebb",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83, participant data matches
ok 84 own UUID is found from the participants list
# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
# teardown
,ok 89 error should be null
ok 90 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60427
2016-04-07 21:25:37.358 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.361 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 e,rror should be null
2016-04-07 21:25:37.363 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.363, ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-07 21:25:37.507 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:37.507 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:37.508 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:37.508 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.508 ThaliTest[2971,:5766834] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 60429
,2016-04-07 21:25:37.723 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
,2016-04-07 21:25:37.723 ThaliTest[2971:5766834] multipeer manager: start client restart timer: 0x14de05c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:37.725 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-07 21:25:37.865 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:37.866 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-07 21:25:38.082 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:38.082 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:38.082 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:38.083 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:38.083 ThaliTest[2971:5766834] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:38.084 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60431
,2016-04-07 21:25:38.642 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:38.642 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:1
2016-04-07 21:25:38.643 ThaliTest[2971:5766834] multipeer m,anager: start client restart timer: 0x14de05c0
2016-04-07 21:25:38.643 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:1
2016-04-07 21:25:38.643 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-07 21:25:38.657 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:25:38.658 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
,2016-04-07 21:25:38.659 ThaliTest[2971:5766834] multipeer manager: stop client timer
,2016-04-07 21:25:38.659 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:2
,2016-04-07 21:25:38.663 ThaliTest[2971:5766834] multipeer manager: start client restart timer: 0x14de05c0
,2016-04-07 21:25:38.667 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:2
,2016-04-07 21:25:38.669 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-07 21:25:39.827 ThaliTest[2971:5766685] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:2
2016-04-07 21:25:39.827 ThaliTest[2971:5766685] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:2
2016-04-07 21:25:39.827 ThaliTest[2971:5766685] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:2
,2016-04-07 21:25:40.742 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:40.743 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:40.743 ThaliTest[2971:5766834] multipeer manager: stop client timer
2016-04-07 21:25:40.743 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:25:40.744 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:40.744 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60436
2016-04-07 21:25:41.339 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:41.340 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:41.340 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-07 21:25:41.343 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:41.343 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:41.343 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-07 21:25:42.132 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:42.132 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:42.132 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:42.132 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:42.133 ThaliTest[2971,:5766834] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60438
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-07 21:25:42.642 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:42.642 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:42.642 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:25:42.643 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:42.643 ThaliTest[2971,:5766834] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60440
2016-04-07 21:25:42.878 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
2016-04-07 21:25:42.878 ThaliTest[2971:5766834] multipeer manager: sta,rt client restart timer: 0x14de05c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:42.879 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:25:42.910 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:42.910 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:3
2016-04-07 21:25:42.911 ThaliTest[2971:5766834] THEMultipee,rManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:3
2016-04-07 21:25:42.911 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches,
# teardown
,2016-04-07 21:25:43.222 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:43.223 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:25:43.223 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:43.223 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:43.223 ThaliTest[2971:5766834] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:43.224 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
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
ok 128 error should be null
# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
# teardown
,ok 130 error should be null
ok 131 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-07 21:26:35.807 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
2016-04-07 21:26:35.807 ThaliTest[2971:5766834] multipeer manager: start client restart timer: 0x14de05c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:35.808 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-07 21:26:35.809 ThaliTes,t[2971:5766834] jxcore: stopListeningForAdvertisements
2016-04-07 21:26:35.809 ThaliTest[2971:5766834] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-07 21:26:35.810 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:26:37.059 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:37.060 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:26:37.061 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:26:37.061 ThaliTest[2971:57668,34] THEMultipeerManager stopping peer
2016-04-07 21:26:37.061 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:26:54.521 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
2016-04-07 21:26:54.522 ThaliTest[2971:5766834] multipeer manager: start client restart timer: 0x14de05c0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:54.526 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAd,vertisements without error
2016-04-07 21:26:54.528 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26,:54.529 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-07 21:26:56.686 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
2016-04-07 21:26:56.687 ThaliTest[2971:5766834] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-07 21:26:56.687 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:26:56.688 ThaliTest[2971:5766,834] jxcore: stopAdvertisingAndListening
2016-04-07 21:26:56.689 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:26:56.689 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:27:21.007 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.008 ThaliTest[2971:57668,34] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-07 21:27:21.009 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.009 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:27:21.149 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:21.150 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:21.152 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.152 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:27:21.152 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:27:21.456 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:21.457 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:4
2016-04-07 21:27:21.457 ThaliTest[2971:5766834] multipeer m,anager: start client restart timer: 0x14de05c0
2016-04-07 21:27:21.457 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:4
2016-04-07 21:27:21.457 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:21.458 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.458 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
,2016-04-07 21:27:21.459 ThaliTest[2971:5766834] multipeer manager: stop client timer
2016-04-07 21:27:21.459 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:27:21.747 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.748 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:21.750 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.750 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:27:21.750 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:27:22.245 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.245 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:5
2016-04-07 21:27:22.245 ThaliTest[2971:5766834] multipeer manager: start client restart timer: 0x14de05c0
2016-04-07 21:27:22.246 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:5
2016-04-07 21:27:22.246 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:22.246 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.247 ThaliTest[2971:5766834] THEMultipeerManager stopping pee,r
2016-04-07 21:27:22.247 ThaliTest[2971:5766834] multipeer manager: stop client timer
2016-04-07 21:27:22.248 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:6
2016-04-07 21:27:22.248 ThaliTest[2971:5766834] multipeer mana,ger: start client restart timer: 0x14de05c0
2016-04-07 21:27:22.252 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:6
2016-04-07 21:27:22.252 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-07 21:27:22.359 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:27:22.361 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:27:22.362 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
,2016-04-07 21:27:22.363 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
,2016-04-07 21:27:22.363 ThaliTest[2971:5766834] multipeer manager: stop client timer
,2016-04-07 21:27:22.365 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:27:51.792 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:51.792 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:27:51.792 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:27:51.793 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:51.793 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
2016-04-07 21:27:51.793 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:27:55.213 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:55.214 ThaliTest[2971:57668,34] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:55.215 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:55.215 ThaliTest[2971:57668,34] THEMultipeerManager stopping peer
2016-04-07 21:27:55.215 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:27:55.502 ThaliTest[2971:5766834] jxcore: connect foo
2016-04-07 21:27:55.502 ThaliTest[2971:5766834] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-07 21:27:55.629 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:55.630 ThaliTest[2971:57668,34] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:55.631 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:55.631 ThaliTest[2971:57668,34] THEMultipeerManager stopping peer
2016-04-07 21:27:55.631 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:27:55.791 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:55.791 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:7
2016-04-07 21:27:55.792 ThaliTest[2971:5766834] multipeer m,anager: start client restart timer: 0x14de05c0
2016-04-07 21:27:55.792 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:7
2016-04-07 21:27:55.792 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-07 21:27:55.793 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-07 21:27:55.794 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:27:56.926 ThaliTest[2971:5766685] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:27:57.020 ThaliTest[2971:5766685] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
,2016-04-07 21:27:57.532 ThaliTest[2971:5766685] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7
,2016-04-07 21:28:01.134 ThaliTest[2971:5766685] client: lost peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499
2016-04-07 21:28:01.135 ThaliTest[2971:5766685] client session: onPeerLost: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499
,2016-04-07 21:28:01.566 ThaliTest[2971:5766685] client: lost peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:28:01.566 ThaliTest[2971:5766685] client session: onPeerLost: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:28:15.793 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:28:15.805 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:28.970 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:28:28.970 ThaliTest[2971:576683,4] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:28:28.971 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:28:28.971 ThaliTest[2971:576683,4] THEMultipeerManager stopping peer
2016-04-07 21:28:28.971 ThaliTest[2971:5766834] multipeer manager: stop client timer
2016-04-07 21:28:28.971 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:28:30.729 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:28:30.729 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:28:30.729 ThaliTest[2971:5766834] multipeer manager: start client restart timer: 0x14de05c0
2016-04-07 21:28:30.729 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:28:30.729 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:28:30.730 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-07 21:28:30.732 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:28:31.483 ThaliTest[2971:5766685] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"750E93F7-2E92-4298-982A-D1BFBCF07,378:7","pleaseConnect":0}]
2016-04-07 21:28:31.485 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:31.485 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:31.485 ThaliTest[2971:5766834] cli,ent session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:33.636 ThaliTest[2971:5766685] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8","pleaseConnect":0}]
,2016-04-07 21:28:34.694 ThaliTest[2971:5766685] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8","pleaseConnect":0}]
,2016-04-07 21:28:35.429 ThaliTest[2971:5767593] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:35.431 ThaliTest[2971:5767593] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:35.4,31 ThaliTest[2971:5767593] client session: disconnect
2016-04-07 21:28:35.431 ThaliTest[2971:5767593] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:35.432 ThaliTest[2971:5767593] client session: fireConnectCallb,ack: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:35.432 ThaliTest[2971:5767593] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-04-07 21:28:38.437 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:38.437 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:38.437 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:38.706 ThaliTest[2971:5767634] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:38.707 ThaliTest[2971:5767634] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:38.7,07 ThaliTest[2971:5767634] client session: disconnect
2016-04-07 21:28:38.707 ThaliTest[2971:5767634] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:38.708 ThaliTest[2971:5767634] client session: fireConnectCallback: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:38.708 ThaliTest[2971:5767634] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:28:41.722 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:41.722 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:41.723 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:42.778 ThaliTest[2971:5767634] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:42.779 ThaliTest[2971:5767634] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:42.7,79 ThaliTest[2971:5767634] client session: disconnect
2016-04-07 21:28:42.779 ThaliTest[2971:5767634] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:42.780 ThaliTest[2971:5767634] client session: fireConnectCallb,ack: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:42.780 ThaliTest[2971:5767634] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:28:45.791 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:45.791 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:45.791 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:46.449 ThaliTest[2971:5767594] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:46.450 ThaliTest[2971:5767594] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:46.4,50 ThaliTest[2971:5767594] client session: disconnect
2016-04-07 21:28:46.450 ThaliTest[2971:5767594] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:46.451 ThaliTest[2971:5767594] client session: fireConnectCallb,ack: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:46.451 ThaliTest[2971:5767594] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-04-07 21:28:49.456 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:49.456 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:49.456 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:7
,2016-04-07 21:28:50.168 ThaliTest[2971:5767594] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:50.169 ThaliTest[2971:5767594] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:50.1,70 ThaliTest[2971:5767594] client session: disconnect
2016-04-07 21:28:50.170 ThaliTest[2971:5767594] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:50.170 ThaliTest[2971:5767594] client session: fireConnectCallb,ack: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:50.170 ThaliTest[2971:5767594] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 5
,2016-04-07 21:28:50.730 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:28:50.745 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:28:50.745 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:28:50.74,5 ThaliTest[2971:5766685] client: found updated peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"750E93F7-2E92-4298-982A-D1BFBCF07378:8","pleaseConnect":0}]
,2016-04-07 21:28:53.184 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:53.185 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:53.185 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:53.820 ThaliTest[2971:5767634] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:53.821 ThaliTest[2971:5767634] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:53.822 ThaliTest[2971:5767634] client session: disconnect
2016-04-07 21:28:53.822 ThaliTest[2971:5767634] client session:, stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:28:53.822 ThaliTest[2971:5767634] client session: fireConnectCallback: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:53.822 ThaliTest[2971:5767634] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:28:56.831 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:28:56.832 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:28:56.832 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:57.441 ThaliTest[2971:5767593] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:57.441 ThaliTest[2971:5767593] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:57.443 ThaliTest[2971:5767593] client session: disconnect
2016-04-07 21:28:57.443 ThaliTest[2971:5767593] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:28:57.443 ThaliTest[2971:5767593] client session: fireConnectCallback: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:28:57.443 ThaliTest[2971:5767593] jxcore: connect: fail: Peer, disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:29:00.452 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:00.452 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:29:00.452 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:00.720 ThaliTest[2971:5767635] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:00.720 ThaliTest[2971:5767635] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:00.7,20 ThaliTest[2971:5767635] client session: disconnect
2016-04-07 21:29:00.721 ThaliTest[2971:5767635] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:00.721 ThaliTest[2971:5767635] client session: fireConnectCallb,ack: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:00.721 ThaliTest[2971:5767635] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:29:03.732 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:03.732 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:29:03.732 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:03.870 ThaliTest[2971:5767594] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:03.870 ThaliTest[2971:5767594] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:03.8,70 ThaliTest[2971:5767594] client session: disconnect
,2016-04-07 21:29:03.870 ThaliTest[2971:5767594] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:03.872 ThaliTest[2971:5767594] client session: fireConnectCallback: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 2,1:29:03.872 ThaliTest[2971:5767594] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:29:06.883 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:7
2016-04-07 21:29:06.883 ThaliTest[2971:5766834] client session: connect
2016-04-07 21:29:06.883 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:29:07.259 ThaliTest[2971:5767593] client session: not connected 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:07.261 ThaliTest[2971:5767593] client session: onLinkFailure: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:07.2,61 ThaliTest[2971:5767593] client session: disconnect
2016-04-07 21:29:07.261 ThaliTest[2971:5767593] client session: stateChange:1->0 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:07.262 ThaliTest[2971:5767593] client session: fireConnectCallb,ack: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:29:07.262 ThaliTest[2971:5767593] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retr,ies!
not ok 177 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-04-07 21:29:10.730 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:29:10.749 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:10.752 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:29:10.752 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:30.730 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:29:30.743 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:30.743 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:29:30.748 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:29:36.439 ThaliTest[2971:5766685] client: lost peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
2016-04-07 21:29:36.439 ThaliTest[2971:5766685] client session: onPeerLost: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9
,2016-04-07 21:29:50.730 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:29:50.742 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:29:50.742 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:50.74,2 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8","pleaseConnect":0}]
,2016-04-07 21:30:10.730 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:30:10.748 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:30:10.749 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:10.74,9 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
,2016-04-07 21:30:30.731 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:30:30.743 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:30:30.743 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:30:30.743 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:30:42.412 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:30:42.413 ThaliTest[2971:5766834] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:30:42.414 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening
2016-04-07 21:30:42.414 ThaliTest[2971:5766834] THEMultipeerManager stopping peer
,2016-04-07 21:30:42.415 ThaliTest[2971:5766834] multipeer manager: stop client timer
2016-04-07 21:30:42.415 ThaliTest[2971:5766834] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 21:30:48.295 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:30:48.295 ThaliTest[2971:5766834] server: starting BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:30:48.296 ThaliTest[2971:5766834] multipeer m,anager: start client restart timer: 0x14de05c0
2016-04-07 21:30:48.296 ThaliTest[2971:5766834] THEMultipeerManager initialized peer BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:30:48.296 ThaliTest[2971:5766834] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:30:48.297 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:30:48.298 ThaliTest[2971:5766834] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 21:30:48.958 ThaliTest[2971:5766685] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:30:48.960 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:30:48.960 ThaliTest[2971:5766834] client session: connect
,2016-04-07 21:30:48.961 ThaliTest[2971:5766834] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:30:50.740 ThaliTest[2971:5766685] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:55.000 ThaliTest[2971:5767747] client session: p2p link connected
,2016-04-07 21:30:55.359 ThaliTest[2971:5767982] client session: stateChange:1->2 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:30:55.360 ThaliTest[2971:5767982] client session: fireConnectCallback: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 21:30:55.360 ThaliTest[2971:5767982] jxcore: connect: success
,2016-04-07 21:30:55.374 ThaliTest[2971:5766685] client: relay established
2016-04-07 21:30:55.375 ThaliTest[2971:5766685] client: new accepted socket: 0x16383e60
,2016-04-07 21:30:55.385 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:30:55.386 ThaliTest[2971:5766834] client: already connect(ing/ed) to 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:30:55.386 ThaliTest[2971:5766834] jxcore: connect: fail: Already connect(ing/ed)
,ok 182 Expected error
,ok 183 Null connection as expected
,2016-04-07 21:30:55.388 ThaliTest[2971:5766834] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:30:55.388 ThaliTest[2971:5766834] client: already connect(ing/ed) to 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:30:55.388 ThaliTest[2971:5766834] jxcore: connect: fail: Already connect(ing/ed)
ok 184 Expected error
ok 185 Null connection as expected
,# teardown
,2016-04-07 21:31:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:31:08.307 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:08.308 ThaliTest[2971:5766685] client: found updated peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:31:28.296 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:31:28.309 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:28.310 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:31:30.402 ThaliTest[2971:5766685] client: found new peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:31:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:31:48.310 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:48.311 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:31:48.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:32:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:08.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:08.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:32:28.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:32:28.315 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:28.316 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:32:48.296 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:32:48.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:48.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:48.313 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:33:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:33:08.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:33:08.31,4 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:33:28.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:33:28.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:33:28.316 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:33:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:33:48.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:33:48.313 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:33:48.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:34:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:34:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:08.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:08.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:34:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:34:28.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:28.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:28.316 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:34:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:34:48.321 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:48.321 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:34:48.32,1 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:35:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:35:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:08.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:35:08.315 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:35:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:35:28.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:35:28.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:28.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:35:48.296 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:35:48.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:48.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:48.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:36:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:36:08.315 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:08.317 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:36:08.317 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:36:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:36:28.315 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:28.315 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:36:28.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:36:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:36:48.323 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:36:48.323 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:36:48.323 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:37:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:37:08.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:08.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:37:08.315 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:37:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:37:28.314 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:37:28.315 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:28.317 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:37:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:37:48.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:37:48.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:48.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:38:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:08.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:38:08.317 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:38:28.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:28.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:38:28.31,3 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:38:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:38:48.314 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:48.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:38:48.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:39:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:39:08.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:39:08.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:08.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:39:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:39:28.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:39:28.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:28.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:39:48.296 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:39:48.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:39:48.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:39:48.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:40:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:40:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:40:08.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:08.31,4 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:40:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:40:28.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:40:28.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:28.316 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:40:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:40:48.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:48.313 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:40:48.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:41:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:41:08.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:41:08.313 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:41:08.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:41:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:41:28.314 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:41:28.316 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:41:28.316 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:41:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:41:48.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:41:48.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:41:48.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:42:08.319 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:08.320 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:08.321 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:42:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:42:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:42:48.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:48.314 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:48.315 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:43:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:43:08.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:43:08.313 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:43:08.31,4 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:43:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:43:28.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:28.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:43:28.316 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:43:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:43:48.314 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:48.315 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:43:48.31,5 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:08.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:44:08.313 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:44:08.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:08.313 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:44:28.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:44:28.312 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:44:28.313 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:28.314 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
,2016-04-07 21:44:48.297 ThaliTest[2971:5766685] multipeer manager: restart client
,2016-04-07 21:44:48.315 ThaliTest[2971:5766685] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:44:48.315 ThaliTest[2971:5766685] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:48.31,5 ThaliTest[2971:5766685] client: found existing peer: E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9

```
