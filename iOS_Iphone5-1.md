#### Test 6568167646f0d89_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/698E69B5-A930-49C8-AE92-34E7FD8635FE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/698E69B5-A930-49C8-AE92-34E7FD8635FE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51859"
,(lldb)     command script import "/tmp/698E69B5-A930-49C8-AE92-34E7FD8635FE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:51:21.573 ThaliTest[2233:6051537] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A7CEAB33-D4BC-4CA0-823F-8CE6BDC7C491/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:51:21.687 ThaliTest[2233:6051537] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:51:21.689 ThaliTest[2233:6051537] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:51:21.708 ThaliTest[2233:6051537] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:51:22.816 ThaliTest[2233:6051537] Using UIWebView
2016-04-07 21:51:22.820 ThaliTest[2233:6051537] [CDVTimer][handleopenurl] 0.260949ms
2016-04-07 21:51:22.825 ThaliTest[2233:6051537] [CDVTimer][intentandnavigationfilter] 4.413009ms
2016-04,-07 21:51:22.825 ThaliTest[2233:6051537] [CDVTimer][gesturehandler] 0.245988ms
2016-04-07 21:51:22.825 ThaliTest[2233:6051537] [CDVTimer][TotalPluginStartup] 5.778015ms
,2016-04-07 21:51:27.537 ThaliTest[2233:6051537] Resetting plugins due to page load.
,2016-04-07 21:51:29.813 ThaliTest[2233:6051537] Finished load of: file:///var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/index.html
,2016-04-07 21:51:30.014 ThaliTest[2233:6051537] JXcore Cordova plugin initializing
,2016-04-07 21:51:30.016 ThaliTest[2233:6051680] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-04-07 21:51:44.198 ThaliTest[2233:6051680] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-07 21:51:44.198 ThaliTest[2233:6051680] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-07 21:51:44.199 ThaliTest[2233:6,051680] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-07 21:51:44.201 ThaliTest[2233:6051680] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9C12CA00-6767-4134-80EF-599653E96AF5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59040
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59042
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59045
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
DEBUG createNativeListener: listening 59049
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 59054
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 59058
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59062
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
DEBUG createNativeListener: listening 59066
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 59070
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 59122
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
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59126
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
ok 52 secondPromise result
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
,ok 67 secondPromise - in then
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
,# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
ok 90 error should be null
# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59136
,2016-04-07 21:54:36.697 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.698 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
,ok 92 error should be null
2016-04-07 21:54:36.703 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54,:36.704 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
,# teardown
,2016-04-07 21:54:36.813 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:36.814 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:54:36.814 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:54:36.814 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:36.817 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59138
2016-04-07 21:54:37.009 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
,2016-04-07 21:54:37.013 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:54:37.014 Th,aliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-07 21:54:37.026 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-07 21:54:37.027 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-07 21:54:37.304 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:37.304 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:54:37.304 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:54:37.304 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
2016-04-07 21:54:37.305 ThaliTest[2233:6051680] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:37.306 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59140
2016-04-07 21:54:37.807 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:54:37.807 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:1
2016-04-07 21:,54:37.808 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
2016-04-07 21:54:37.808 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:1
2016-04-07 21:54:37.808 ThaliTest[2233,:6051680] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-07 21:54:37.827 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:54:37.828 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
,2016-04-07 21:54:37.829 ThaliTest[2233:6051680] multipeer manager: stop client timer
,2016-04-07 21:54:37.833 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:2
,2016-04-07 21:54:37.835 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
,2016-04-07 21:54:37.842 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:2
,2016-04-07 21:54:37.843 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-07 21:54:37.976 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:37.977 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:54:37.977 ThaliTest[2233:6051680] multipeer manager: stop client timer
20,16-04-07 21:54:37.977 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:54:37.978 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:37.979 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59145
,2016-04-07 21:55:02.104 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:02.104 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:55:02.104 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
2016-04-07 21:55:02.108 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:02.108 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:55:02.108 ,ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-07 21:55:02.393 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:02.394 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
,2016-04-07 21:55:02.395 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:55:02.395 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"a,dvertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:02.396 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59147
,ok 115 first call should succeed
ok 116 first call should succeed
,ok 117 specific error should be returned
# teardown
,2016-04-07 21:55:05.515 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.515 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:55:05.515 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:55:05.516 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:05.517 ThaliTest[2233,:6051680] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59149
2016-04-07 21:55:05.709 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
2016-04-07 21:55:05.710 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:05.711 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:55:05.724 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:55:05.724 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:3
2016-04-07 21:55:05.725 ThaliTest[2233:6051680] THEMultipee,rManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:3
2016-04-07 21:55:05.725 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-07 21:55:05.967 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.968 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:55:05.968 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:55:05.968 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:05.968 ThaliTest[2233:6051680] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:05.969 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-07 21:55:56.564 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
2016-04-07 21:55:56.564 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:56.565 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-07 21:55:56.566 ThaliTes,t[2233:6051680] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:56.567 ThaliTest[2233:6051680] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-07 21:55:56.567 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:55:56.954 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:56.955 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:55:56.957 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:56.957 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:55:56.957 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:55:57.476 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
2016-04-07 21:55:57.476 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.477 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
,2016-04-07 21:55:57.479 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.480 ThaliTest[2233:60516,80] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-07 21:55:57.563 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:57.563 ThaliTest[2233:6051680] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-07 21:55:57.564 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:55:57.565 ThaliTest[2233:6051,680] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:57.565 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:55:57.566 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:56:09.573 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:09.574 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-07 21:56:09.575 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:09.576 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:56:22.584 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.585 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:22.586 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.586 ThaliTest[2233:60516,80] THEMultipeerManager stopping peer
2016-04-07 21:56:22.586 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:56:22.748 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:22.748 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:4
2016-04-07 21:56:22.749 ThaliTest[2233:6051680] multipeer manager: start client restart timer: 0x14df2690
,2016-04-07 21:56:22.751 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:4
,2016-04-07 21:56:22.765 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:56:22.768 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
,2016-04-07 21:56:22.770 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
,2016-04-07 21:56:22.775 ThaliTest[2233:6051680] multipeer manager: stop client timer
,2016-04-07 21:56:22.776 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:56:23.014 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:23.015 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:23.016 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:23.016 ThaliTest[2233:60516,80] THEMultipeerManager stopping peer
2016-04-07 21:56:23.016 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:56:23.221 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:23.221 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:5
2016-04-07 21:56:23.222 ThaliTest[2233:6051680] multipeer m,anager: start client restart timer: 0x14df2690
2016-04-07 21:56:23.222 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:5
2016-04-07 21:56:23.222 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:23.223 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:23.224 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
,2016-04-07 21:56:23.224 ThaliTest[2233:6051680] multipeer manager: stop client timer
2016-04-07 21:56:23.231 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:6
2016-04-07 21:56:23.231 ThaliTest[2233:6051680] multipeer manager,: start client restart timer: 0x14df2690
2016-04-07 21:56:23.232 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:6
2016-04-07 21:56:23.232 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-07 21:56:23.629 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:56:23.630 ThaliTest[2233:605168,0] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:23.630 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:23.631 ThaliTest[2233:605168,0] THEMultipeerManager stopping peer
2016-04-07 21:56:23.631 ThaliTest[2233:6051680] multipeer manager: stop client timer
2016-04-07 21:56:23.631 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:56:25.611 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:25.611 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:56:25.611 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:25.612 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:25.613 ThaliTest[2233:6051680] THEMultipeerManager stopping peer
2016-04-07 21:56,:25.613 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-07 21:56:43.157 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:43.158 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:43.159 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:43.159 ThaliTest[2233:60516,80] THEMultipeerManager stopping peer
2016-04-07 21:56:43.159 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:57:10.420 ThaliTest[2233:6051680] jxcore: connect foo
2016-04-07 21:57:10.421 ThaliTest[2233:6051680] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvert,isements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-07 21:57:16.445 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:57:16.446 ThaliTest[2233:60516,80] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:16.447 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:16.448 ThaliTest[2233:60516,80] THEMultipeerManager stopping peer
2016-04-07 21:57:16.448 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:57:16.832 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:57:16.832 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:16.833 ThaliTest[2233:6051680] multipeer m,anager: start client restart timer: 0x14df2690
2016-04-07 21:57:16.833 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:16.833 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-07 21:57:16.834 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-07 21:57:16.835 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:18.425 ThaliTest[2233:6051537] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a strin,g
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:57:18.820 ThaliTest[2233:6051537] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
,2016-04-07 21:57:18.879 ThaliTest[2233:6051537] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
,2016-04-07 21:57:19.620 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:57:19.621 ThaliTest[2233:605168,0] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:19.622 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:19.622 ThaliTest[2233:605168,0] THEMultipeerManager stopping peer
2016-04-07 21:57:19.623 ThaliTest[2233:6051680] multipeer manager: stop client timer
2016-04-07 21:57:19.623 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:57:20.227 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:57:20.227 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:20.228 ThaliTest[2233:6051680] multipeer m,anager: start client restart timer: 0x14df2690
2016-04-07 21:57:20.228 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:20.228 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:57:20.229 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-07 21:57:20.230 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:20.919 ThaliTest[2233:6051537] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E495F,C9C:7","pleaseConnect":0}]
2016-04-07 21:57:20.921 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:20.922 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:20.922 ThaliTest[2233:6051680] cli,ent session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:21.243 ThaliTest[2233:6051537] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFE,FEE:7","pleaseConnect":0}]
2016-04-07 21:57:21.249 ThaliTest[2233:6052318] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:21.249 ThaliTest[2233:6052318] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E49,5FC9C
2016-04-07 21:57:21.250 ThaliTest[2233:6052318] client session: disconnect
2016-04-07 21:57:21.250 ThaliTest[2233:6052318] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:21.251 ThaliTest[2233:6052318] clie,nt session: fireConnectCallback: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:21.251 ThaliTest[2233:6052318] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileN,ative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:57:22.290 ThaliTest[2233:6051537] multipeer session: reset timer
,2016-04-07 21:57:22.290 ThaliTest[2233:6051537] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:57:22.664 ThaliTest[2233:6051537] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8","pleaseConnect":0}]
,2016-04-07 21:57:24.107 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:57:24.108 ThaliTest[2233:6051537] server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:57:24.264 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:24.265 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:24.265 ThaliTest[2233:6051680] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:24.653 ThaliTest[2233:6052338] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:24.655 ThaliTest[2233:6052338] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:24.6,55 ThaliTest[2233:6052338] client session: disconnect
2016-04-07 21:57:24.655 ThaliTest[2233:6052338] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:24.656 ThaliTest[2233:6052338] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:24.656 ThaliTest[2233:6052338] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:57:27.663 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:27.663 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:27.663 ThaliTest[2233:6051680] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:27.863 ThaliTest[2233:6052318] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:27.864 ThaliTest[2233:6052318] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:27.8,64 ThaliTest[2233:6052318] client session: disconnect
2016-04-07 21:57:27.864 ThaliTest[2233:6052318] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:27.866 ThaliTest[2233:6052318] client session: fireConnectCallback: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:27.866 ThaliTest[2233:6052318] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:57:30.875 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:30.875 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:30.876 ThaliTest[2233:6051680] client session: stateChange:0->,1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:31.029 ThaliTest[2233:6052318] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:31.030 ThaliTest[2233:6052318] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
,2016-04-07 21:57:31.032 ThaliTest[2233:6052318] client session: disconnect
2016-04-07 21:57:31.032 ThaliTest[2233:6052318] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:31.032 ThaliTest[2233:6052318] client sess,ion: fireConnectCallback: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:31.032 ThaliTest[2233:6052318] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: ,Scheduling a connect retry - retries left: 6
,2016-04-07 21:57:34.044 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:34.044 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:34.044 ThaliTest[2233:6051680] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:34.080 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:57:34.081 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 21:57:34.081 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:57:34.186 ThaliTest[2233:6052317] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:34.186 ThaliTest[2233:6052317] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:34.1,86 ThaliTest[2233:6052317] client session: disconnect
2016-04-07 21:57:34.186 ThaliTest[2233:6052317] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:34.187 ThaliTest[2233:6052317] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:34.187 ThaliTest[2233:6052317] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:57:35.265 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:57:35.265 ThaliTest[2233:6051537] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 21:57:35.265 ThaliTest[2233:6051537], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:57:37.190 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:37.190 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:37.190 ThaliTest[2233:6051680] client session: stateChange:0->,1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
,2016-04-07 21:57:37.296 ThaliTest[2233:6052317] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:37.297 ThaliTest[2233:6052317] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:37.2,98 ThaliTest[2233:6052317] client session: disconnect
2016-04-07 21:57:37.298 ThaliTest[2233:6052317] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:37.299 ThaliTest[2233:6052317] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:37.299 ThaliTest[2233:6052317] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-04-07 21:57:40.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:57:40.256 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:57:40.256 ThaliTest[2233:6051537] client: found updated peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
INFO testThaliMobileNat,ive: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8","pleaseConnect":0}]
,2016-04-07 21:57:40.268 ThaliTest[2233:6051537] client: found updated peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E,495FC9C:8","pleaseConnect":0}]
,2016-04-07 21:57:40.306 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:40.306 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:40.306 ThaliTest[2233:6051680] client session: stateChange:0->,1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:57:40.445 ThaliTest[2233:6052317] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:40.445 ThaliTest[2233:6052317] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:40.4,45 ThaliTest[2233:6052317] client session: disconnect
2016-04-07 21:57:40.445 ThaliTest[2233:6052317] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:40.446 ThaliTest[2233:6052317] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:40.446 ThaliTest[2233:6052317] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-04-07 21:57:43.457 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:43.458 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:43.458 ThaliTest[2233:6051680] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:57:44.065 ThaliTest[2233:6052342] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:44.066 ThaliTest[2233:6052342] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:44.0,66 ThaliTest[2233:6052342] client session: disconnect
2016-04-07 21:57:44.067 ThaliTest[2233:6052342] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:44.068 ThaliTest[2233:6052342] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:44.068 ThaliTest[2233:6052342] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:57:47.078 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:47.078 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:47.078 ThaliTest[2233:6051680] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:57:47.259 ThaliTest[2233:6052317] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:47.259 ThaliTest[2233:6052317] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:47.2,59 ThaliTest[2233:6052317] client session: disconnect
2016-04-07 21:57:47.261 ThaliTest[2233:6052317] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:57:47.267 ThaliTest[2233:6052317] client session: fireConnectCallback: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:47.267 ThaliTest[2233:6052317] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
2016-04-07 21:57:47.269 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:57:47.269 ThaliTest[2233:6051537] server: disconnecting t,o refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 21:57:47.269 ThaliTest[2233:6051537] server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-,B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:57:48.309 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:57:48.309 ThaliTest[2233:6051537] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 21:57:48.309 ThaliTest[2233:6051537], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:57:50.276 ThaliTest[2233:6051680] jxcore: connect 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:50.277 ThaliTest[2233:6051680] client session: connect
2016-04-07 21:57:50.277 ThaliTest[2233:6051680] client session: stateChange:0->1 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:57:50.412 ThaliTest[2233:6052317] client session: not connected 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:50.413 ThaliTest[2233:6052317] client session: onLinkFailure: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:50.4,14 ThaliTest[2233:6052317] client session: disconnect
2016-04-07 21:57:50.415 ThaliTest[2233:6052317] client session: stateChange:1->0 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:57:50.415 ThaliTest[2233:6052317] client session: fireConnectCallb,ack: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 21:57:50.415 ThaliTest[2233:6052317] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retr,ies!
not ok 177 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-04-07 21:58:00.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:58:00.262 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:00.262 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:58:00.26,4 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:01.473 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:58:01.473 ThaliTest[2233:6051537] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 21:58:01.473 ThaliTest[2233:6051537], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:58:05.658 ThaliTest[2233:6051537] client: lost peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 21:58:05.658 ThaliTest[2233:6051537] client session: onPeerLost: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 21:58:14.585 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:58:14.585 ThaliTest[2233:6051537] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 21:58:14.586 ThaliTest[2233:6051537], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:58:18.997 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8","pleaseConnect":0}]
,2016-04-07 21:58:20.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:58:20.258 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:58:20.258 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:58:26.567 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:58:27.582 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 21:58:27.583 ThaliTest[2233:6051537] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 21:58:27.583 ThaliTest[2233:6051537], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7)
,2016-04-07 21:58:40.228 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:58:40.275 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:40.276 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:40.283 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:58:57.031 ThaliTest[2233:6051537] client: lost peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 21:58:57.032 ThaliTest[2233:6051537] client session: onPeerLost: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 21:59:00.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:59:00.247 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:59:00.247 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
INFO testThaliMobileNa,tive: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8","pleaseConnect":0}]
,2016-04-07 21:59:00.253 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:59:20.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:59:20.255 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:20.265 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:59:20.265 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:59:40.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 21:59:40.255 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:59:40.258 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:59:40.259 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 21:59:49.710 ThaliTest[2233:6051537] client: lost peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 21:59:49.711 ThaliTest[2233:6051537] client session: onPeerLost: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 21:59:50.765 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8","pleaseConnect":0}]
,2016-04-07 22:00:00.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:00:00.259 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:00.260 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 22:00:00.26,0 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:20.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:00:20.265 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:20.266 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:20.269 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:39.108 ThaliTest[2233:6051537] client: lost peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
2016-04-07 22:00:39.108 ThaliTest[2233:6051537] client session: onPeerLost: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C
,2016-04-07 22:00:40.229 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:00:40.260 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 22:00:40.260 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
INFO testThaliMobileNa,tive: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8","pleaseConnect":0}]
2016-04-07 22:00:40.266 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
,2016-04-07 22:00:43.193 ThaliTest[2233:6051537] client: lost peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559
2016-04-07 22:00:43.194 ThaliTest[2233:6051537] client session: onPeerLost: D42275B6-6BF0-48D7-8A46-E91B6C0E6559
,2016-04-07 22:00:43.204 ThaliTest[2233:6051537] client: lost peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
2016-04-07 22:00:43.204 ThaliTest[2233:6051537] client session: onPeerLost: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE
,2016-04-07 22:00:51.628 ThaliTest[2233:6051680] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 22:00:51.629 ThaliTest[2233:605168,0] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 22:00:51.630 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening
2016-04-07 22:00:51.630 ThaliTest[2233:605168,0] THEMultipeerManager stopping peer
2016-04-07 22:00:51.631 ThaliTest[2233:6051680] multipeer manager: stop client timer
2016-04-07 22:00:51.631 ThaliTest[2233:6051680] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdve,rtisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 22:00:55.669 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndListening
2016-04-07 22:00:55.670 ThaliTest[2233:6051680] server: starting EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:00:55.670 ThaliTest[2233:6051680] multipeer m,anager: start client restart timer: 0x14df2690
2016-04-07 22:00:55.670 ThaliTest[2233:6051680] THEMultipeerManager initialized peer EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:00:55.671 ThaliTest[2233:6051680] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-07 22:00:55.672 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-07 22:00:55.673 ThaliTest[2233:6051680] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 22:00:57.332 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:00:57.332 ThaliTest[2233:6051537] server: rejecting invitation from D42275B6-6BF0-48D7-8A46-E91B6C0E6559 due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:00:57.649 ThaliTest[2233:6051537] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:00:57.650 ThaliTest[2233:6051537] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:00:57.650 ThaliTes,t[2233:6051680] jxcore: connect D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:00:57.651 ThaliTest[2233:6051680] client session: connect
2016-04-07 22:00:57.651 ThaliTest[2233:6051680] client session: stateChange:0->1 D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:00:58.975 ThaliTest[2233:6051537] client: found new peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:00.106 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:01:00.107 ThaliTest[2233:6051537] server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:01:00.620 ThaliTest[2233:6053053] client session: p2p link connected
2016-04-07 22:01:00.623 ThaliTest[2233:6053053] client session: stateChange:1->2 D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:00.623 ThaliTest[2233:6053053] cli,ent session: fireConnectCallback: D42275B6-6BF0-48D7-8A46-E91B6C0E6559
2016-04-07 22:01:00.623 ThaliTest[2233:6053053] jxcore: connect: success
,2016-04-07 22:01:00.640 ThaliTest[2233:6051680] jxcore: connect D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:00.641 ThaliTest[2233:6051680] client: already connect(ing/ed) to D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:00.641 Thali,Test[2233:6051680] jxcore: connect: fail: Already connect(ing/ed)
ok 182 Expected error
ok 183 Null connection as expected
2016-04-07 22:01:00.642 ThaliTest[2233:6051680] jxcore: connect D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:00.643 Th,aliTest[2233:6051680] client: already connect(ing/ed) to D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:00.643 ThaliTest[2233:6051680] jxcore: connect: fail: Already connect(ing/ed)
ok 184 Expected error
ok 185 Null connection as expected
# te,ardown
2016-04-07 22:01:00.647 ThaliTest[2233:6051537] client: relay established
2016-04-07 22:01:00.647 ThaliTest[2233:6051537] client: new accepted socket: 0x1b6b8390
,2016-04-07 22:01:13.252 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:01:13.253 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:01:13.253 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:01:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:01:15.690 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:15.704 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:15.705 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:01:26.361 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:01:26.362 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:01:26.362 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:01:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:01:35.708 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:35.709 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:35.71,0 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:01:39.426 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:01:39.426 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:01:39.426 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:01:52.958 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:01:52.958 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:01:52.958 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:01:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:01:55.710 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:55.710 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:55.71,2 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:05.670 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:02:05.671 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
,2016-04-07 22:02:05.671 ThaliTest[2233:6051537] server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:02:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:02:15.707 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:02:15.707 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:02:15.70,8 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:02:18.200 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:02:18.200 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:02:18.200 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:02:31.366 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:02:31.366 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:02:31.366 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:02:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:02:35.696 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:02:35.696 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:02:35.69,7 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:02:44.473 ThaliTest[2233:6051537] multipeer session: reset timer
2016-04-07 22:02:44.474 ThaliTest[2233:6051537] server: disconnecting to refresh session (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE)
2016-04-07 22:02:44.474 ThaliTest[2233:6051537], server: rejecting invitation from 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE due to previous generation (EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9 != EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8)
,2016-04-07 22:02:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:02:55.706 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:02:55.706 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:02:55.708 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:03:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:03:15.701 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:03:15.701 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:15.70,1 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:03:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:03:35.706 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:03:35.706 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:35.70,7 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:03:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:03:55.700 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:03:55.702 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:55.70,2 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:04:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:04:15.708 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:04:15.709 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:15.71,0 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:04:35.671 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:04:35.704 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:35.705 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:04:35.70,5 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:04:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:04:55.707 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:55.707 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:04:55.70,9 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:05:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:05:15.699 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:05:15.701 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:05:15.705 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:05:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:05:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:05:55.693 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:05:55.693 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:05:55.694 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:06:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:06:15.692 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:06:15.692 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:15.69,3 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:06:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:06:35.693 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:06:35.693 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:06:35.69,4 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:06:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:06:55.690 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:06:55.691 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:55.69,1 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:07:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:07:15.695 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:15.695 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:07:15.69,5 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:07:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:07:35.692 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:07:35.696 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:35.69,6 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:07:55.671 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:07:55.693 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:07:55.694 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:55.69,4 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:08:15.671 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:08:15.689 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:15.690 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:08:15.69,0 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:08:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:08:35.692 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:35.692 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:08:35.69,3 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:08:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:08:55.693 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:55.693 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:08:55.69,4 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:09:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:09:15.689 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:15.689 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:09:15.69,0 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:09:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:09:35.693 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:35.693 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:09:35.694 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:09:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:09:55.688 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:55.689 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:09:55.69,0 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:10:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:10:15.689 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:15.690 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:10:15.690 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:10:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:10:35.693 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:10:35.694 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:10:35.69,5 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:10:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:10:55.694 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:10:55.694 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:55.69,4 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:11:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:11:15.690 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:15.691 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:11:15.691 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:11:35.671 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:11:35.691 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:35.692 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:11:35.69,2 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:11:55.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:11:55.692 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:55.692 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:11:55.693 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:12:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:12:15.696 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:15.697 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:15.69,7 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:12:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:12:35.694 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:35.695 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:12:35.69,5 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:12:55.671 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:12:55.690 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:12:55.692 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:55.692 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
,2016-04-07 22:13:15.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:13:15.692 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:13:15.692 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:13:15.69,3 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:13:35.672 ThaliTest[2233:6051537] multipeer manager: restart client
,2016-04-07 22:13:35.693 ThaliTest[2233:6051537] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:13:35.693 ThaliTest[2233:6051537] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:13:35.69,4 ThaliTest[2233:6051537] client: found existing peer: 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9

```
