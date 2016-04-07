#### Test 6568167646f0d89_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/2006F8EB-0DDA-4879-8EAB-3E1463A64228/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2006F8EB-0DDA-4879-8EAB-3E1463A64228/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51861"
,(lldb)     command script import "/tmp/2006F8EB-0DDA-4879-8EAB-3E1463A64228/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:51:48.707 ThaliTest[2926:5787677] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF0FA14B-C26B-4F6F-A6F1-8F4C506FCB7C/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:51:48.933 ThaliTest[2926:5787677] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:51:48.934 ThaliTest[2926:5787677] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:51:48.949 ThaliTest[2926:5787677] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:51:49.704 ThaliTest[2926:5787677] Using UIWebView
,2016-04-07 21:51:49.707 ThaliTest[2926:5787677] [CDVTimer][handleopenurl] 0.324011ms
,2016-04-07 21:51:49.709 ThaliTest[2926:5787677] [CDVTimer][intentandnavigationfilter] 2.465010ms
2016-04-07 21:51:49.710 ThaliTest[2926:5787677] [CDVTimer][gesturehandler] 0.122011ms
2016-04-07 21:51:49.710 ThaliTest[2926:5787677] [CDVTimer][TotalPluginS,tartup] 3.448009ms
,2016-04-07 21:51:52.722 ThaliTest[2926:5787677] Resetting plugins due to page load.
,2016-04-07 21:51:54.058 ThaliTest[2926:5787677] Finished load of: file:///var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/index.html
,2016-04-07 21:51:54.216 ThaliTest[2926:5787677] JXcore Cordova plugin initializing
,2016-04-07 21:51:54.217 ThaliTest[2926:5787842] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:52:01.271 ThaliTest[2926:5787842] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-07 21:52:01.271 ThaliTest[2926:5787842] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-07 21:52:01.272 ThaliTest[2926:5787842] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-07 21:52:01.274 ThaliTest[2926:5787842] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D34995E-22BC-4A73-AA1B-1523310E7924/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58201
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58203
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58206
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58210
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
,DEBUG createNativeListener: listening 58215
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
,DEBUG createNativeListener: listening 58219
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
DEBUG createNativeListener: listening 58223
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
DEBUG createNativeListener: listening 58227
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 Th,e mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58231
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creati,ng incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 58283
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 58287
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
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
,# teardown
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
,ok 59 secondPromise - second to run
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
ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
,# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
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
,[{"uuid":"0a5569ba-1ed4-436a-9411-0f7974f7bbc6","data":"custom data"},{"uuid":"dcb5d381-cae6-4f05-8e4a-e2d4f542730f","data":"custom data"},{"uuid":"a01448f3-8faa-4a3b-be30-b4d35e539833","data":"custom data"},{"uuid":"6d9c6404-32a9-487f-ab25-46f5222cb94f",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
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
DEBUG createNativeListener: listening 58297
2016-04-07 21:54:36.620 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.622 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 e,rror should be null
2016-04-07 21:54:36.623 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.624, ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-07 21:54:36.772 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:36.772 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:54:36.772 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:54:36.773 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.773 ThaliTest[2926,:5787842] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58299
2016-04-07 21:54:36.970 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
2016-04-07 21:54:36.971 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:54:36.971 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-07 21:54:36.976 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-07 21:54:36.977 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-07 21:54:37.265 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:37.265 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:54:37.265 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:54:37.266 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
2016-04-07 21:54:37.266 ThaliTest[2926:5787842] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:37.266 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be ,null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58301
,2016-04-07 21:54:37.747 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:54:37.748 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:1
,2016-04-07 21:54:37.749 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
,2016-04-07 21:54:37.752 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:1
,2016-04-07 21:54:37.752 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-07 21:54:37.772 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:54:37.772 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
,2016-04-07 21:54:37.773 ThaliTest[2926:5787842] multipeer manager: stop client timer
,2016-04-07 21:54:37.775 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:2
,2016-04-07 21:54:37.776 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
,2016-04-07 21:54:37.778 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:2
,2016-04-07 21:54:37.779 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-07 21:54:37.925 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:37.925 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:54:37.926 ThaliTest[2926:5787842] multipeer manager: stop client timer
2016-04-07 21:54:37.926 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:54:37.926 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:37.927 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58306
,2016-04-07 21:54:40.353 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:40.354 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:54:40.354 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
,2016-04-07 21:54:40.356 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:40.356 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:54:40.356 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: suc,cess
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-07 21:55:02.240 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:02.240 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:55:02.240 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:55:02.240 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:02.241 ThaliTest[2926,:5787842] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58308
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-07 21:55:05.466 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.466 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:55:05.466 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:55:05.467 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:05.467 ThaliTest[2926,:5787842] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58310
2016-04-07 21:55:05.660 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
2016-04-07 21:55:05.660 ThaliTest[2926:5787842] multipeer manager: sta,rt client restart timer: 0x175733e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:05.661 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:55:05.666 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:55:05.666 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:3
2016-04-07 21:55:05.666 ThaliTest[2926:5787842] THEMultipee,rManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:3
2016-04-07 21:55:05.666 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-07 21:55:05.937 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.937 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:55:05.938 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:55:05.938 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:05.938 ThaliTest[2926:5787842] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:05.938 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
ok 126 should not have been called more than once
# teardown
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
,ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-07 21:55:56.512 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
2016-04-07 21:55:56.512 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:56.513 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-07 21:55:56.513 ThaliTes,t[2926:5787842] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:56.514 ThaliTest[2926:5787842] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-07 21:55:56.514 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:55:56.860 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:56.860 ThaliTest[2926:57878,42] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:55:56.861 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:56.861 ThaliTest[2926:57878,42] THEMultipeerManager stopping peer
2016-04-07 21:55:56.861 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:55:57.421 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
2016-04-07 21:55:57.421 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.422 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-07 21:55:57.423 ThaliTes,t[2926:5787842] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.423 ThaliTest[2926:5787842] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-07 21:55:57.521 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:57.521 ThaliTest[2926:5787842] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-07 21:55:57.522 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:55:57.522 ThaliTest[2926:5787,842] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:57.522 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:55:57.522 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:56:13.035 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:13.035 ThaliTest[2926:57878,42] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-07 21:56:13.036 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:13.036 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:56:22.456 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.457 ThaliTest[2926:57878,42] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:22.457 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.458 ThaliTest[2926:57878,42] THEMultipeerManager stopping peer
2016-04-07 21:56:22.458 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:56:22.705 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:22.705 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:4
2016-04-07 21:56:22.705 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
2016-04-07 21:56:22.705 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:4
2016-04-07 21:56:22.705 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:22.706 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.706 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
,2016-04-07 21:56:22.706 ThaliTest[2926:5787842] multipeer manager: stop client timer
2016-04-07 21:56:22.710 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-07 21:56:22.952 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.953 ThaliTest[2926:57878,42] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:22.954 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.954 ThaliTest[2926:57878,42] THEMultipeerManager stopping peer
2016-04-07 21:56:22.954 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:56:23.467 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:23.467 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:5
2016-04-07 21:56:23.467 ThaliTest[2926:5787842] multipeer m,anager: start client restart timer: 0x175733e0
2016-04-07 21:56:23.468 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:5
2016-04-07 21:56:23.468 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:23.468 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:23.469 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
,2016-04-07 21:56:23.469 ThaliTest[2926:5787842] multipeer manager: stop client timer
2016-04-07 21:56:23.471 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:6
2016-04-07 21:56:23.471 ThaliTest[2926:5787842] multipeer manager,: start client restart timer: 0x175733e0
2016-04-07 21:56:23.471 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:6
2016-04-07 21:56:23.471 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-07 21:56:23.586 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:56:23.587 ThaliTest[2926:578784,2] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:23.587 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:23.587 ThaliTest[2926:578784,2] THEMultipeerManager stopping peer
2016-04-07 21:56:23.588 ThaliTest[2926:5787842] multipeer manager: stop client timer
2016-04-07 21:56:23.588 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:56:25.296 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:25.296 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:56:25.297 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:25.297 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:25.298 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:56:25.298 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:56:44.892 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:44.892 ThaliTest[2926:57878,42] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:44.893 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:44.893 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:56:44.893 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:57:12.332 ThaliTest[2926:5787842] jxcore: connect foo
2016-04-07 21:57:12.332 ThaliTest[2926:5787842] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-07 21:57:16.417 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:57:16.418 ThaliTest[2926:57878,42] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:16.419 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:16.419 ThaliTest[2926:57878,42] THEMultipeerManager stopping peer
2016-04-07 21:57:16.419 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:57:16.683 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:57:16.683 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
2016-04-07 21:57:16.684 ThaliTest[2926:5787842] multipeer m,anager: start client restart timer: 0x175733e0
2016-04-07 21:57:16.684 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
2016-04-07 21:57:16.684 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-07 21:57:16.685 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-07 21:57:16.685 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:17.724 ThaliTest[2926:5787677] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:57:17.846 ThaliTest[2926:5787677] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:18.845 ThaliTest[2926:5787677] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:19.582 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:57:19.583 ThaliTest[2926:578784,2] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:19.583 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:19.583 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 21:57:19.583 ThaliTest[2926:5787842] multipeer manager: stop client timer
2016-04-07 21:57:19.583 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:57:20.194 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:57:20.195 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:57:20.195 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
2016-04-07 21:57:20.195 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:57:20.195 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:57:20.196 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:57:20.196 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:21.203 ThaliTest[2926:5787677] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:21.203 ThaliTest[2926:5787677] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7","pleaseConnect":0}]
2016-04-07 21:57:21.204 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:21.205 ThaliTest[2926:5787842] client session: connect
,2016-04-07 21:57:21.205 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7","pleaseConnect":0}]
,2016-04-07 21:57:21.260 ThaliTest[2926:5787677] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7","pleaseConnect":0}]
,2016-04-07 21:57:22.795 ThaliTest[2926:5788523] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:22.795 ThaliTest[2926:5788523] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:22.795 ThaliTest[2926:5788523] client session: disconnect
2016-04-07 21:57:22.796 ThaliTest[2926:5788523] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:22.796 ThaliTest[2926:5788523] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:22.796 ThaliTest[2926:5788523] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:57:25.809 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:25.809 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:57:25.809 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:26.968 ThaliTest[2926:5788524] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:26.968 ThaliTest[2926:5788524] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:26.968 ThaliTest[2926:5788524] client session: disconnect
2016-04-07 21:57:26.968 ThaliTest[2926:5788524] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:26.968 ThaliTest[2926:5788524] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:26.968 ThaliTest[2926:5788524] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:57:29.974 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:29.975 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:57:29.975 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:30.522 ThaliTest[2926:5788524] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:30.522 ThaliTest[2926:5788524] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:30.5,22 ThaliTest[2926:5788524] client session: disconnect
2016-04-07 21:57:30.522 ThaliTest[2926:5788524] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:30.522 ThaliTest[2926:5788524] client session: fireConnectCallback: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:30.522 ThaliTest[2926:5788524] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-04-07 21:57:33.525 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:33.525 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:57:33.525 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:33.703 ThaliTest[2926:5788542] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:33.704 ThaliTest[2926:5788542] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:33.704 ThaliTest[2926:5788542] client session: disconnect
2016-04-07 21:57:33.704 ThaliTest[2926:5788542] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:33.704 ThaliTest[2926:5788542] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:33.704 ThaliTest[2926:5788542] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:57:36.709 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:36.710 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:57:36.710 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:37.054 ThaliTest[2926:5788542] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:37.054 ThaliTest[2926:5788542] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:37.0,54 ThaliTest[2926:5788542] client session: disconnect
2016-04-07 21:57:37.054 ThaliTest[2926:5788542] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:37.054 ThaliTest[2926:5788542] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:37.054 ThaliTest[2926:5788542] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 5
,2016-04-07 21:57:40.060 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:40.060 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:57:40.060 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:40.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:57:40.208 ThaliTest[2926:5787677] client: found updated peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:40.208 ThaliTest[2926:5787677] client: found updated peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:57:40.208 ThaliTest[2926:5787677] client: found updated peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8","pleaseConnec,t":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{",peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8","pleaseConnect":0}]
,2016-04-07 21:58:00.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:58:00.211 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:58:00.214 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:58:00.215 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:13.064 ThaliTest[2926:5788626] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:13.065 ThaliTest[2926:5788626] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:58:13.065 ThaliTest[2926:5788626] client session: disconnect
2016-04-07 21:58:13.065 ThaliTest[2926:5788626] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:13.065 ThaliTest[2926:5788626] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:58:13.065 ThaliTest[2926:5788626] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:58:16.077 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:58:16.077 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:58:16.077 ThaliTest[2926:5787842] client session: stateChange:0->,1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:58:20.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:58:20.207 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:58:20.207 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:20.207 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:58:40.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:58:40.210 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:40.211 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:40.214 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:58:49.035 ThaliTest[2926:5788721] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:49.035 ThaliTest[2926:5788721] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:58:49.0,35 ThaliTest[2926:5788721] client session: disconnect
2016-04-07 21:58:49.035 ThaliTest[2926:5788721] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:49.035 ThaliTest[2926:5788721] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:58:49.035 ThaliTest[2926:5788721] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-04-07 21:58:52.048 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:58:52.049 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:58:52.049 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:00.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:59:00.212 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:59:00.212 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:59:00.213 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:59:20.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:59:20.211 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:59:20.211 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:20.215 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:59:25.044 ThaliTest[2926:5788886] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:59:25.045 ThaliTest[2926:5788886] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:59:25.045 ThaliTest[2926:5788886] client session: disconnect
2016-04-07 21:59:25.045 ThaliTest[2926:5788886] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:25.047 ThaliTest[2926:5788886] client session: fireConnectCallback: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:59:25.047 ThaliTest[2926:5788886] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:59:28.053 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:59:28.053 ThaliTest[2926:5787842] client session: connect
2016-04-07 21:59:28.053 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:40.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 21:59:40.210 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:59:40.210 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:59:40.210 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 22:00:00.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:00:00.205 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 22:00:00.206 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 22:00:00.207 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:01.024 ThaliTest[2926:5789041] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:01.024 ThaliTest[2926:5789041] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 22:00:01.024 ThaliTest[2926:5789041] client session: disconnect
2016-04-07 22:00:01.024 ThaliTest[2926:5789041] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:01.024 ThaliTest[2926:5789041] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 22:00:01.024 ThaliTest[2926:5789041] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 22:00:04.038 ThaliTest[2926:5787842] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 22:00:04.038 ThaliTest[2926:5787842] client session: connect
2016-04-07 22:00:04.038 ThaliTest[2926:5787842] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 22:00:20.196 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:00:20.208 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:20.208 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:20.208 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:37.035 ThaliTest[2926:5789041] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:37.035 ThaliTest[2926:5789041] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 22:00:37.035 ThaliTest[2926:5789041] client session: disconnect
2016-04-07 22:00:37.035 ThaliTest[2926:5789041] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:37.035 ThaliTest[2926:5789041] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 22:00:37.035 ThaliTest[2926:5789041] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-04-07 22:00:37.698 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 22:00:37.699 ThaliTest[2926:5787842] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 22:00:37.700 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening
2016-04-07 22:00:37.700 ThaliTest[2926:5787842] THEMultipeerManager stopping peer
2016-04-07 22:00:37.701 ThaliTest[2926:5787842] multipeer manager: stop client timer
20,16-04-07 22:00:37.701 ThaliTest[2926:5787842] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 22:00:55.663 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening
2016-04-07 22:00:55.663 ThaliTest[2926:5787842] server: starting D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:00:55.664 ThaliTest[2926:5787842] multipeer manager: start client restart timer: 0x175733e0
2016-04-07 22:00:55.664 ThaliTest[2926:5787842] THEMultipeerManager initialized peer D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:00:55.664 ThaliTest[2926:5787842] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 22:00:55.665 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-07 22:00:55.666 ThaliTest[2926:5787842] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 22:00:56.389 ThaliTest[2926:5787677] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:56.390 ThaliTest[2926:5787842] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:56.390 ThaliTest[2926:5787842] client: server will connect
,2016-04-07 22:00:56.390 ThaliTest[2926:5787842] client session: reverseConnect
2016-04-07 22:00:56.391 ThaliTest[2926:5787842] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 22:00:56.826 ThaliTest[2926:5787677] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:56.966 ThaliTest[2926:5787677] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 22:00:57.290 ThaliTest[2926:5789186] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:57.291 ThaliTest[2926:5789186] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:00:57.2,91 ThaliTest[2926:5789186] client session: disconnect
2016-04-07 22:00:57.291 ThaliTest[2926:5789186] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:57.291 ThaliTest[2926:5789186] client session: no connect callb,ack (server initiated)
,2016-04-07 22:00:57.940 ThaliTest[2926:5787677] multipeer session: reset timer
2016-04-07 22:00:57.941 ThaliTest[2926:5787677] server session: connect
2016-04-07 22:00:57.941 ThaliTest[2926:5787677] server session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:00:57.945 ThaliTest[2926:5787677] server: accepting invitation EA14B348-B7C0-4A23-9984-3BE67FDBCA34
,2016-04-07 22:01:00.562 ThaliTest[2926:5789207] server session: p2p link connected
,2016-04-07 22:01:00.579 ThaliTest[2926:5787677] server relay: connected (to port: 58344)
2016-04-07 22:01:00.580 ThaliTest[2926:5787677] server session: stateChange:1->2 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:00.580 ThaliTest[2926:5787677] jxcore: connect: success
,2016-04-07 22:01:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:01:15.678 ThaliTest[2926:5787677] client: found updated peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:15.678 ThaliTest[2926:5787677] client: found updated peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:01:15.679 ThaliTest[2926:5787677] client: found updated peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:15.679 ThaliTest[2926:5787842] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:15.679 ThaliTest[2926:5787842] client: serv,er already connected
2016-04-07 22:01:15.679 ThaliTest[2926:5787842] jxcore: connect: success
,2016-04-07 22:01:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:01:35.674 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:35.675 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:01:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:01:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:01:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:55.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:55.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:02:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:02:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:02:35.677 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:35.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:55.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:02:55.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:55.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:03:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:03:15.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:03:15.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:15.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:03:35.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:03:35.680 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:03:35.681 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:03:35.681 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:03:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:03:55.677 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:55.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:03:55.677 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:04:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:04:15.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:15.675 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:04:15.675 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:04:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:04:35.680 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:35.682 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:04:35.682 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:04:55.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:04:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:04:55.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:55.677 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:05:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:05:15.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:05:15.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:05:15.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:05:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:05:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:05:35.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:05:35.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:05:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:05:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:05:55.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:05:55.677 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:06:15.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:06:15.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:15.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:06:15.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:06:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:06:35.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:06:35.675 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:06:35.675 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:06:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:06:55.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:06:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:55.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:07:15.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:07:15.679 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:15.679 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:07:15.679 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:07:35.674 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:07:35.674 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:07:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:07:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:07:55.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:55.677 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:07:55.677 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:08:15.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:08:15.681 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:08:15.681 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:08:15.68,1 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:08:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:08:35.680 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:08:35.681 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:08:35.681 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:08:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:08:55.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:08:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:08:55.67,6 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:09:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:09:15.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:09:15.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:15.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:09:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:09:35.680 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:09:35.680 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:35.680 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:09:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:09:55.679 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:55.680 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:09:55.680 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:10:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:10:15.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:10:15.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:10:15.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:10:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:10:35.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:10:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:10:35.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:10:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:10:55.675 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:10:55.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:10:55.678 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:11:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:11:15.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:11:15.675 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:11:15.677 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:11:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:11:35.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:11:35.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:11:35.678 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:11:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:11:55.679 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:11:55.679 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:11:55.683 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:12:15.665 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:12:15.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:12:15.677 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:15.677 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:12:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:12:35.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:12:35.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:12:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:12:55.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:12:55.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:55.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:12:55.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:13:15.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:13:15.675 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:13:15.675 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:13:15.675 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:13:35.664 ThaliTest[2926:5787677] multipeer manager: restart client
,2016-04-07 22:13:35.676 ThaliTest[2926:5787677] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:13:35.676 ThaliTest[2926:5787677] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:13:35.676 ThaliTest[2926:5787677] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9

```
