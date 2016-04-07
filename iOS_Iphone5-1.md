#### Test 656816764cf5745_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/427AFCFA-9214-459A-9300-64A34874369E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/427AFCFA-9214-459A-9300-64A34874369E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/656816764cf5745/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51794"
,(lldb)     command script import "/tmp/427AFCFA-9214-459A-9300-64A34874369E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:22:26.029 ThaliTest[2221:6047264] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0BB169D-40E8-4CE5-B6E1-51D889F5A317/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:22:26.126 ThaliTest[2221:6047264] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:22:26.129 ThaliTest[2221:6047264] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:22:26.152 ThaliTest[2221:6047264] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:22:27.301 ThaliTest[2221:6047264] Using UIWebView
2016-04-07 21:22:27.307 ThaliTest[2221:6047264] [CDVTimer][handleopenurl] 0.302970ms
,2016-04-07 21:22:27.312 ThaliTest[2221:6047264] [CDVTimer][intentandnavigationfilter] 4.765034ms
2016-04-07 21:22:27.313 ThaliTest[2221:6047264] [CDVTimer][gesturehandler] 0.218987ms
2016-04-07 21:22:27.313 ThaliTest[2221:6047264] [CDVTimer][TotalPluginStartup] 6.139994ms
,2016-04-07 21:22:32.041 ThaliTest[2221:6047264] Resetting plugins due to page load.
,2016-04-07 21:22:34.117 ThaliTest[2221:6047264] Finished load of: file:///var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/index.html
,2016-04-07 21:22:34.307 ThaliTest[2221:6047264] JXcore Cordova plugin initializing
,2016-04-07 21:22:34.309 ThaliTest[2221:6047377] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:22:48.475 ThaliTest[2221:6047377] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-07 21:22:48.476 ThaliTest[2221:6047377] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-07 21:22:48.477 ThaliTest[2221:6047377] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-07 21:22:48.480 ThaliTest[2221:6047377] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7411341F-931B-416E-B857-DA59D0A10CD2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58852
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58854
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
DEBUG createNativeListener: listening 58857
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
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58861
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58866
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
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58870
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 58874
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: listening 58878
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed,
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58882
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
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creat,ing incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creat,ing incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: listening 58934
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
DEBUG createNativeListener: listening 58938
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,ok 49 firstPromise result
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
,[{"uuid":"03445e62-5e92-48cc-8875-30b0fdcb1b59","data":"custom data"},{"uuid":"cc977dc9-3774-4da7-8114-07bc6d4a1955","data":"custom data"},{"uuid":"856d22a5-0926-412e-b7a9-ad2877c2c912","data":"custom data"},{"uuid":"1019d4f9-108b-42a3-b511-e8f2013d3ebb",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
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
DEBUG createNativeListener: listening 58948
2016-04-07 21:25:37.472 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.473 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-07 21:25:37.476 ThaliTest[2221:6047377] jx,core: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:25:37.479 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-07 21:25:37.598 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:37.598 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:37.598 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:37.598 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:37.599 ThaliTest[2221,:6047377] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
,ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58950
,2016-04-07 21:25:37.814 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
,2016-04-07 21:25:37.816 ThaliTest[2221:6047377] multipeer manager: start client restart timer: 0x145d61b0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:25:37.818 Th,aliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-07 21:25:37.829 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-04-07 21:25:37.830 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-07 21:25:38.160 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:38.161 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:38.161 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:38.161 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:38.161 ThaliTest[2221:6047377] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:38.162 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58952
,2016-04-07 21:25:38.734 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:38.734 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:1
2016-04-07 21:25:38.735 ThaliTest[2221:6047377] multipeer m,anager: start client restart timer: 0x145d61b0
2016-04-07 21:25:38.735 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:1
2016-04-07 21:25:38.736 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-07 21:25:38.747 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:38.748 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:38.748, ThaliTest[2221:6047377] multipeer manager: stop client timer
2016-04-07 21:25:38.748 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:2
2016-04-07 21:25:38.749 ThaliTest[2221:6047377] multipeer manager: start client restart ,timer: 0x145d61b0
2016-04-07 21:25:38.749 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:2
2016-04-07 21:25:38.749 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-07 21:25:39.905 ThaliTest[2221:6047264] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:2
2016-04-07 21:25:39.906 ThaliTest[2221:6047264] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:2
,2016-04-07 21:25:40.740 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:40.740 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:40.741 ThaliTest[2221:6047377] multipeer manager: stop client timer
20,16-04-07 21:25:40.741 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:25:40.741 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:40.742 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58957
,2016-04-07 21:25:41.754 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:41.754 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:41.754 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
,2016-04-07 21:25:41.757 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:41.758 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:41.758 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-07 21:25:42.210 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:42.211 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:42.211 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:42.211 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:42.212 ThaliTest[2221,:6047377] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58959
,ok 115 first call should succeed
ok 116 first call should succeed
,ok 117 specific error should be returned
# teardown
,2016-04-07 21:25:42.725 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:42.725 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:42.725 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:42.726 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:42.727 ThaliTest[2221,:6047377] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58961
2016-04-07 21:25:42.965 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
2016-04-07 21:25:42.966 ThaliTest[2221:6047377] multipeer manager: start client restart timer: 0x145d61b0
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:25:42.967 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:25:42.999 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:25:43.000 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:3
2016-04-07 21:25:43.000 ThaliTest[2221:6047377] THEMultipee,rManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:3
2016-04-07 21:25:43.000 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-07 21:25:43.302 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:25:43.303 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:25:43.303 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:25:43.303 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
2016-04-07 21:25:43.303 ThaliTest[2221:6047377] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:25:43.304 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
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
,# setup
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
ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-07 21:26:12.478 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
2016-04-07 21:26:12.479 ThaliTest[2221:6047377] multipeer manager: start client restart timer: 0x145d61b0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:26:12.480 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-07 21:26:12.482 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
2016-04,-07 21:26:12.482 ThaliTest[2221:6047377] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:12.483 ThaliTest[2221:6047377] jxcor,e: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:26:36.034 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:26:36.035 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:26:36.036 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:26:36.036 ThaliTest[2221:60473,77] THEMultipeerManager stopping peer
2016-04-07 21:26:36.036 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:26:54.546 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
2016-04-07 21:26:54.547 ThaliTest[2221:6047377] multipeer manager: start client restart timer: 0x145d61b0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:54.548 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-07 21:26:54.549 ThaliTes,t[2221:6047377] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:26:54.550 ThaliTest[2221:6047377] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-07 21:26:55.335 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
2016-04-07 21:26:55.335 ThaliTest[2221:6047377] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-07 21:26:55.336 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:26:55.337 ThaliTest[2221:6047,377] jxcore: stopAdvertisingAndListening
2016-04-07 21:26:55.337 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:26:55.337 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdv,ertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:27:21.099 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:27:21.100 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
2016-04-07 21:27:21.102 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discove,ryActive":false}
2016-04-07 21:27:21.103 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:27:21.305 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.306 ThaliTest[2221:60473,77] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:21.307 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.307 ThaliTest[2221:60473,77] THEMultipeerManager stopping peer
2016-04-07 21:27:21.307 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:27:21.512 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:21.512 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:4
2016-04-07 21:27:21.513 ThaliTest[2221:6047377] multipeer m,anager: start client restart timer: 0x145d61b0
2016-04-07 21:27:21.513 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:4
2016-04-07 21:27:21.513 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:21.514 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.515 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
,2016-04-07 21:27:21.515 ThaliTest[2221:6047377] multipeer manager: stop client timer
2016-04-07 21:27:21.520 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-07 21:27:21.833 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:21.834 ThaliTest[2221:60473,77] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:21.835 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:21.835 ThaliTest[2221:60473,77] THEMultipeerManager stopping peer
2016-04-07 21:27:21.835 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:27:22.297 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.297 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:5
2016-04-07 21:27:22.298 ThaliTest[2221:6047377] multipeer m,anager: start client restart timer: 0x145d61b0
2016-04-07 21:27:22.298 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:5
2016-04-07 21:27:22.298 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:22.299 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:22.299 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
,2016-04-07 21:27:22.300 ThaliTest[2221:6047377] multipeer manager: stop client timer
2016-04-07 21:27:22.307 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:6
2016-04-07 21:27:22.307 ThaliTest[2221:6047377] multipeer manager,: start client restart timer: 0x145d61b0
2016-04-07 21:27:22.307 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:6
2016-04-07 21:27:22.307 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-07 21:27:22.443 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:27:22.444 ThaliTest[2221:604737,7] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:22.445 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:22.445 ThaliTest[2221:604737,7] THEMultipeerManager stopping peer
2016-04-07 21:27:22.445 ThaliTest[2221:6047377] multipeer manager: stop client timer
2016-04-07 21:27:22.445 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:27:44.247 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:44.247 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:27:44.247 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:27:44.248 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:44.248 ThaliTest[2221:6047377] THEMultipeerManager stopping peer
2016-04-07 21:27,:44.248 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:27:52.050 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:52.051 ThaliTest[2221:60473,77] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:52.052 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:52.052 ThaliTest[2221:60473,77] THEMultipeerManager stopping peer
2016-04-07 21:27:52.053 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:27:55.585 ThaliTest[2221:6047377] jxcore: connect foo
2016-04-07 21:27:55.586 ThaliTest[2221:6047377] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-07 21:27:55.713 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:27:55.714 ThaliTest[2221:60473,77] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:27:55.715 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:27:55.715 ThaliTest[2221:60473,77] THEMultipeerManager stopping peer
2016-04-07 21:27:55.715 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:27:55.899 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:27:55.900 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
2016-04-07 21:27:55.900 ThaliTest[2221:6047377] multipeer m,anager: start client restart timer: 0x145d61b0
2016-04-07 21:27:55.900 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7
2016-04-07 21:27:55.901 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-07 21:27:55.902 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-07 21:27:55.903 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:27:57.920 ThaliTest[2221:6047264] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:7
2016-04-07 21:27:57.920 ThaliTest[2221:6047264] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:7
ok 167 peers must be an array
o,k 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:28:00.494 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:28:00.495 ThaliTest[2221:604737,7] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:28:00.496 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:28:00.496 ThaliTest[2221:604737,7] THEMultipeerManager stopping peer
2016-04-07 21:28:00.496 ThaliTest[2221:6047377] multipeer manager: stop client timer
2016-04-07 21:28:00.496 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:28:30.823 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:28:30.823 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:28:30.823 ThaliTest[2221:6047377] multipeer m,anager: start client restart timer: 0x145d61b0
2016-04-07 21:28:30.824 ThaliTest[2221:6047377] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8
2016-04-07 21:28:30.824 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:28:30.825 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-07 21:28:30.826 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:28:32.880 ThaliTest[2221:6047264] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:28:32.881 ThaliTest[2221:6047264] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8","pleaseConnect":0}]
2016-04-07 21:28:32.882 ThaliTest[2221:6047377] jxcore: connect 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:28:32.883 ThaliTest[2221:6047377] client session: connect
2016-04-07 21:28:32.887 ThaliTest[2221:6047377] client session: stateChange:0->1 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"750E93F7-2E92-4298-982A-D1BFBCF07378:8","pleaseConnect":0}]
,2016-04-07 21:28:35.310 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:28:35.311 ThaliTest[2221:6047264] server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A,97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:28:38.345 ThaliTest[2221:6048119] client session: p2p link connected
2016-04-07 21:28:38.348 ThaliTest[2221:6048119] client session: stateChange:1->2 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:28:38.349 ThaliTest[2221:6048119] cli,ent session: fireConnectCallback: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499
2016-04-07 21:28:38.349 ThaliTest[2221:6048119] jxcore: connect: success
INFO testThaliMobileNative: 
ok 177 Must have listeningPort
ok 178 listeningPort must be a number
ok 179 Co,nnection must have clientPort
ok 180 clientPort must be a number
ok 181 Connection must have serverPort
ok 182 serverPort must be a number
ok 183 forward connection must have clientPort == 0
,ok 184 forward connection must have serverPort == 0
,# teardown
,2016-04-07 21:28:46.193 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:28:46.194 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:28:46.194 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:28:50.825 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:28:50.861 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:28:50.865 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
,2016-04-07 21:28:53.571 ThaliTest[2221:6047264] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BF68E1C5-762A-429C-BDD9-41F21131A115:8","pleaseConnect":0}]
,2016-04-07 21:28:58.196 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:28:58.197 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:28:58.197 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:29:10.824 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:29:10.865 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:10.866 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,2016-04-07 21:29:11.614 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:29:11.614 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:29:11.614 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:29:24.655 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:29:24.656 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:29:24.656 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:29:30.825 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:29:37.564 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:29:37.564 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:29:37.564 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:29:50.602 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:29:50.602 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:29:50.602 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:29:50.825 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:29:50.840 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
,2016-04-07 21:29:50.844 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:29:50.845 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:03.276 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:30:03.277 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:30:03.277 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:30:10.825 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:30:10.842 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:30:10.844 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:10.84,5 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:16.293 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:30:16.293 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:30:16.294 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:30:29.386 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:30:29.386 ThaliTest[2221:6047264] server: disconnecting to refresh session (750E93F7-2E92-4298-982A-D1BFBCF07378)
2016-04-07 21:30:29.386 ThaliTest[2221:6047264], server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:7)
,2016-04-07 21:30:30.825 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:30:30.871 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:8
2016-04-07 21:30:30.871 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:8
2016-04-07 21:30:30.87,3 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:41.314 ThaliTest[2221:6048453] client session: not connected 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
2016-04-07 21:30:41.314 ThaliTest[2221:6048453] client session: onLinkFailure: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499
2016-04-07 21:30:41.3,14 ThaliTest[2221:6048453] client session: disconnect
2016-04-07 21:30:41.315 ThaliTest[2221:6048453] client session: stateChange:2->0 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:8
,2016-04-07 21:30:42.375 ThaliTest[2221:6047264] client: lost peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499
2016-04-07 21:30:42.376 ThaliTest[2221:6047264] client session: onPeerLost: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499
,2016-04-07 21:30:42.607 ThaliTest[2221:6047377] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:30:42.608 ThaliTest[2221:604737,7] jxcore: stopListeningForAdvertisements: success
ok 185 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:30:42.608 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening
2016-04-07 21:30:42.609 ThaliTest[2221:604737,7] THEMultipeerManager stopping peer
2016-04-07 21:30:42.609 ThaliTest[2221:6047377] multipeer manager: stop client timer
2016-04-07 21:30:42.609 ThaliTest[2221:6047377] jxcore: stopAdvertisingAndListening: success
ok 186 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 21:31:29.619 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening
,2016-04-07 21:31:29.621 ThaliTest[2221:6047377] server: starting E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:31:29.622 ThaliTest[2221:6047377] multipeer manager: start client restart timer: 0x145d61b0
2016-04-07 21:31:29.622 ThaliTest[2221:60473,77] THEMultipeerManager initialized peer E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9
2016-04-07 21:31:29.622 ThaliTest[2221:6047377] jxcore: startUpdateAdvertisingAndListening: success
ok 187 Can call startUpdateAdvertisingAndListening without error
2016-04-,07 21:31:29.623 ThaliTest[2221:6047377] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-07 21:31:29.624 ThaliTest[2221:6047377] jxcor,e: startListeningForAdvertisements: success
ok 188 Can call startListeningForAdvertisements without error
,2016-04-07 21:31:29.649 ThaliTest[2221:6047264] client: found new peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:29.653 ThaliTest[2221:6047264] client: found new peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:31:29.658 ThaliTest[2221:6047377] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:29.660 ThaliTest[2221:6047264] client: found new peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:31:29.666 ThaliTest[2221:6047377] client session: connect
,2016-04-07 21:31:29.668 ThaliTest[2221:6047377] client session: stateChange:0->1 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:30.465 ThaliTest[2221:6047264] multipeer session: reset timer
2016-04-07 21:31:30.465 ThaliTest[2221:6047264] server: rejecting invitation from 750E93F7-2E92-4298-982A-D1BFBCF07378 due to previous generation (E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:9 != E1F1EF18-2DA6-44FB-A6A3-9631A97782C9:8)
,2016-04-07 21:31:33.813 ThaliTest[2221:6048591] client session: p2p link connected
,2016-04-07 21:31:33.827 ThaliTest[2221:6048563] client session: stateChange:1->2 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:33.827 ThaliTest[2221:6048563] client session: fireConnectCallback: 750E93F7-2E92-4298-982A-D1BFBCF07378
2016-04-07 2,1:31:33.828 ThaliTest[2221:6048563] jxcore: connect: success
,2016-04-07 21:31:33.843 ThaliTest[2221:6047377] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:33.844 ThaliTest[2221:6047377] client: already connect(ing/ed) to 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:33.844 Thali,Test[2221:6047377] jxcore: connect: fail: Already connect(ing/ed)
ok 189 Expected error
ok 190 Null connection as expected
2016-04-07 21:31:33.845 ThaliTest[2221:6047377] jxcore: connect 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:33.846 Th,aliTest[2221:6047377] client: already connect(ing/ed) to 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:31:33.846 ThaliTest[2221:6047377] jxcore: connect: fail: Already connect(ing/ed)
ok 191 Expected error
ok 192 Null connection as expected
# te,ardown
2016-04-07 21:31:33.850 ThaliTest[2221:6047264] client: relay established
2016-04-07 21:31:33.850 ThaliTest[2221:6047264] client: new accepted socket: 0x1a6a0430
,2016-04-07 21:31:49.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:31:49.642 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:31:49.642 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:31:49.985 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:32:09.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:32:09.645 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:09.645 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:09.646 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:32:29.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:32:29.659 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:32:29.660 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:29.66,0 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:32:49.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:32:49.646 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:32:49.646 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:32:49.647 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:33:09.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:33:09.647 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:09.647 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:33:09.64,7 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:33:29.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:33:29.649 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:29.650 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:33:29.65,0 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:33:49.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:33:49.647 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:33:49.647 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:33:49.64,8 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:34:09.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:34:09.645 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:09.645 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:09.646 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:34:29.623 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:34:29.646 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:29.646 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:34:29.64,6 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:34:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:34:49.576 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:34:49.576 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:34:49.57,6 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:35:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:35:09.578 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:35:09.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:09.57,9 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:35:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:35:29.576 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:29.577 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:29.579 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:35:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:35:49.580 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:35:49.581 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:35:49.581 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:36:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:36:09.581 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:09.581 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:36:09.581 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:36:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:36:29.576 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:29.577 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:36:29.577 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:36:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:36:49.579 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:36:49.580 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:36:49.580 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:37:09.556 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:37:09.576 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:09.580 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:37:09.58,0 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:37:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:37:29.578 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:37:29.580 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:29.58,0 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:37:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:37:49.578 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:37:49.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:37:49.580 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:38:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:38:09.579 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:38:09.579 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:09.57,9 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:38:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:38:29.577 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:38:29.577 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:38:29.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:38:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:38:49.583 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:38:49.585 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:38:49.585 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:39:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:39:09.580 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:09.580 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:09.580 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:39:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:39:29.580 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:39:29.580 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:29.58,1 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:39:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:39:49.576 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:39:49.577 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:39:49.57,7 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:40:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:40:09.577 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:09.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:09.57,8 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:40:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:40:29.580 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:29.580 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:40:29.58,0 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:40:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:40:49.574 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:40:49.574 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:40:49.57,5 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:41:09.556 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:41:09.579 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:41:09.580 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:41:09.58,0 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:41:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:41:29.576 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:41:29.576 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:41:29.57,6 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:41:49.556 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:41:49.577 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:41:49.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:41:49.578 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:42:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:42:09.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:09.580 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:09.58,1 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:42:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:42:29.577 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:29.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:29.57,8 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:42:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:42:49.580 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:42:49.580 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:42:49.58,1 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:43:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:43:09.580 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:09.581 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:09.58,1 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
,2016-04-07 21:43:29.556 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:43:29.576 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:43:29.577 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:43:29.57,8 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:43:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:43:49.579 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:43:49.579 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:43:49.57,9 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:44:09.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:44:09.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:09.579 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:44:09.579 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
,2016-04-07 21:44:29.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:44:29.578 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9
2016-04-07 21:44:29.579 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:29.57,9 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
,2016-04-07 21:44:49.557 ThaliTest[2221:6047264] multipeer manager: restart client
,2016-04-07 21:44:49.578 ThaliTest[2221:6047264] client: found existing peer: 3A9DE2CF-AEE1-4BE9-994B-D8804B4E2499:9
2016-04-07 21:44:49.579 ThaliTest[2221:6047264] client: found existing peer: BF68E1C5-762A-429C-BDD9-41F21131A115:9
2016-04-07 21:44:49.57,9 ThaliTest[2221:6047264] client: found existing peer: 750E93F7-2E92-4298-982A-D1BFBCF07378:9

```
