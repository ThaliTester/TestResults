#### Test 6568167646f0d89_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/46F40C6E-9BCF-4223-8173-99A42EC8BC2D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/46F40C6E-9BCF-4223-8173-99A42EC8BC2D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6568167646f0d89/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51863"
,(lldb)     command script import "/tmp/46F40C6E-9BCF-4223-8173-99A42EC8BC2D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-07 21:51:50.216 ThaliTest[2984:5770988] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35BB22B0-DDFB-4314-9971-FBCCCFC64C46/Library/Cookies/Cookies.binarycookies
,2016-04-07 21:51:50.459 ThaliTest[2984:5770988] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-07 21:51:50.460 ThaliTest[2984:5770988] Multi-tasking -> Device: YES, App: YES
,2016-04-07 21:51:50.478 ThaliTest[2984:5770988] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-07 21:51:51.258 ThaliTest[2984:5770988] Using UIWebView
,2016-04-07 21:51:51.262 ThaliTest[2984:5770988] [CDVTimer][handleopenurl] 0.178039ms
2016-04-07 21:51:51.265 ThaliTest[2984:5770988] [CDVTimer][intentandnavigationfilter] 2.602041ms
2016-04-07 21:51:51.266 ThaliTest[2984:5770988] [CDVTimer][gesturehandler] 0.118971ms
2016-04-07 21:51:51.266 ThaliTest[2984:5770988] [CDVTimer][TotalPluginStartup] 3.508985ms
,2016-04-07 21:51:54.336 ThaliTest[2984:5770988] Resetting plugins due to page load.
,2016-04-07 21:51:55.579 ThaliTest[2984:5770988] Finished load of: file:///var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/index.html
,2016-04-07 21:51:55.769 ThaliTest[2984:5770988] JXcore Cordova plugin initializing
,2016-04-07 21:51:55.770 ThaliTest[2984:5771138] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-07 21:52:04.175 ThaliTest[2984:5771138] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-07 21:52:04.176 ThaliTest[2984:5771138] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-07 21:52:04.176 ThaliTest[2984:5,771138] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-07 21:52:04.179 ThaliTest[2984:5771138] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1193D90D-E52E-4E2E-88A1-0DF9CACF1259/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-07 21:52:11.780 ThaliTest[2984:5770988] THREAD WARNING: ['JXcore'] took '7239.407959' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60536
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60538
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
,DEBUG createNativeListener: listening 60541
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
,DEBUG createNativeListener: listening 60545
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 60550
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
DEBUG createNativeListener: listening 60554
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 60558
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
DEBUG createNativeListener: listening 60562
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60566
,DEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
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
DEBUG createNativeListener: listening 60618
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 60622
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
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
,ok 49 firstPromise result
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
,# teardown
,# setup
,# 21. another
,ok 75 sane
,# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"0a5569ba-1ed4-436a-9411-0f7974f7bbc6","data":"custom data"},{"uuid":"dcb5d381-cae6-4f05-8e4a-e2d4f542730f","data":"custom data"},{"uuid":"a01448f3-8faa-4a3b-be30-b4d35e539833","data":"custom data"},{"uuid":"6d9c6404-32a9-487f-ab25-46f5222cb94f","data":"custom data"}]
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
DEBUG createNativeListener: listening 60632
2016-04-07 21:54:36.599 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.600 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-07 21:54:36.602 ThaliTest[2984:5771138] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.602 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: succes,s
ok 93 error should be null
,ok 94 error should be null
# teardown
,2016-04-07 21:54:36.749 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:36.750 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:54:36.750 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:54:36.750 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:36.751 ThaliTest[2984,:5771138] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60634
2016-04-07 21:54:36.941 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
,2016-04-07 21:54:36.943 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:54:36.945 Th,aliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-07 21:54:36.995 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:54:36.996 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-07 21:54:37.251 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:37.251 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:54:37.251 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:54:37.252 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
2016-04-07 21:54:37.252 ThaliTest[2984:5771138] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:54:37.253 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60636
,2016-04-07 21:54:37.739 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:54:37.740 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:1
,2016-04-07 21:54:37.742 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
2016-04-07 21:54:37.742 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:1
2016-04-07 21:54:37.742 ,ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-07 21:54:37.754 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:54:37.754 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:54:37.755, ThaliTest[2984:5771138] multipeer manager: stop client timer
2016-04-07 21:54:37.755 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:2
2016-04-07 21:54:37.755 ThaliTest[2984:5771138] multipeer manager: start client restart ,timer: 0x15dbc4c0
2016-04-07 21:54:37.759 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:2
2016-04-07 21:54:37.759 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-07 21:54:37.911 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:37.911 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:54:37.911 ThaliTest[2984:5771138] multipeer manager: stop client timer
20,16-04-07 21:54:37.911 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:54:37.912 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-07 21:54:37.912 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60641
2016-04-07 21:54:39.432 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:39.432 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:54:39.432 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
,2016-04-07 21:54:39.435 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:54:39.435 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:54:39.435 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-07 21:55:05.047 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.048 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:55:05.048 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
2016-04-07 21:55:05.048 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:05.049 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60643
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-07 21:55:05.454 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.454 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:55:05.454 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:55:05.454 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:05.455 ThaliTest[2984,:5771138] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 60645
2016-04-07 21:55:05.632 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
2016-04-07 21:55:05.633 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-07 21:55:05.633 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
,2016-04-07 21:55:05.675 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:55:05.676 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:3
2016-04-07 21:55:05.676 ThaliTest[2984:5771138] THEMultipee,rManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:3
2016-04-07 21:55:05.676 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-07 21:55:05.909 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:05.909 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:55:05.909 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-07 21:55:05.910 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:05.910 ThaliTest[2984:5771138] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:05.911 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
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
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-07 21:55:56.493 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
2016-04-07 21:55:56.494 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:56.494 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
2016-04-07 21:55:56.496 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:56.496 ThaliTest[2984:5771138] multipeer manager: stop client timer
DEBUG thaliMobileNa,tiveWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:56.497 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-07 21:55:56.835 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-07 21:55:56.836 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:55:56.838 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:56.838 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:55:56.838 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-07 21:55:57.413 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
2016-04-07 21:55:57.414 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.415 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-07 21:55:57.415 ThaliTes,t[2984:5771138] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-07 21:55:57.416 ThaliTest[2984:5771138] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-07 21:55:57.492 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
2016-04-07 21:55:57.493 ThaliTest[2984:5771138] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:55:57.494 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:55:57.494 ThaliTest[2984:5771,138] jxcore: stopAdvertisingAndListening
2016-04-07 21:55:57.494 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:55:57.494 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-07 21:56:22.244 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.245 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-07 21:56:22.245 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.246 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-07 21:56:22.385 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.386 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:56:22.387 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.387 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:56:22.387 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-07 21:56:22.681 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:22.681 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:4
2016-04-07 21:56:22.681 ThaliTest[2984:5771138] multipeer m,anager: start client restart timer: 0x15dbc4c0
2016-04-07 21:56:22.681 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:4
2016-04-07 21:56:22.682 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:22.683 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.684 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:56:22.68,4 ThaliTest[2984:5771138] multipeer manager: stop client timer
2016-04-07 21:56:22.684 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-07 21:56:22.826 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:56:22.827 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:56:22.827 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:22.827 ThaliTest[2984:57711,38] THEMultipeerManager stopping peer
2016-04-07 21:56:22.827 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-07 21:56:23.466 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:56:23.466 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:5
2016-04-07 21:56:23.466 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
2016-04-07 21:56:23.466 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:5
,2016-04-07 21:56:23.469 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:56:23.470 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListenin,g
2016-04-07 21:56:23.470 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:56:23.470 ThaliTest[2984:5771138] multipeer manager: stop client timer
2016-04-07 21:56:23.470 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-,B795-F4E22EFFEFEE:6
2016-04-07 21:56:23.471 ThaliTest[2984:5771138] multipeer manager: start client restart timer: 0x15dbc4c0
2016-04-07 21:56:23.471 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:6
,2016-04-07 21:56:23.471 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-07 21:56:23.565 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-07 21:56:23.566 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-07 21:56:23.567 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:23.567 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:56:23.568 ThaliTest[2984:5771138] multipeer manager: stop client timer
20,16-04-07 21:56:23.568 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-07 21:56:30.157 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:30.157 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:56:30.158 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-07 21:56:30.159 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:56:30.159 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:56:30.159 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-07 21:57:04.165 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:57:04.166 ThaliTest[2984:57711,38] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:04.166 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
,2016-04-07 21:57:04.166 ThaliTest[2984:5771138] THEMultipeerManager stopping peer
2016-04-07 21:57:04.168 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-07 21:57:16.199 ThaliTest[2984:5771138] jxcore: connect foo
2016-04-07 21:57:16.199 ThaliTest[2984:5771138] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-07 21:57:16.333 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-07 21:57:16.334 ThaliTest[2984:57711,38] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:16.335 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:16.335 ThaliTest[2984:57711,38] THEMultipeerManager stopping peer
2016-04-07 21:57:16.335 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-07 21:57:16.663 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:57:16.664 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
2016-04-07 21:57:16.664 ThaliTest[2984:5771138] multipeer m,anager: start client restart timer: 0x15dbc4c0
2016-04-07 21:57:16.664 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:7
2016-04-07 21:57:16.664 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-07 21:57:16.665 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
,2016-04-07 21:57:16.666 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:17.864 ThaliTest[2984:5770988] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
2016-04-07 21:57:17.864 ThaliTest[2984:5770988] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-07 21:57:18.854 ThaliTest[2984:5770988] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:19.553 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 21:57:19.554 ThaliTest[2984:577113,8] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 21:57:19.555 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 21:57:19.555 ThaliTest[2984:577113,8] THEMultipeerManager stopping peer
2016-04-07 21:57:19.555 ThaliTest[2984:5771138] multipeer manager: stop client timer
2016-04-07 21:57:19.555 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-07 21:57:20.164 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 21:57:20.165 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:57:20.165 ThaliTest[2984:5771138] multipeer m,anager: start client restart timer: 0x15dbc4c0
2016-04-07 21:57:20.165 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8
2016-04-07 21:57:20.165 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-07 21:57:20.166 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-07 21:57:20.167 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-07 21:57:20.803 ThaliTest[2984:5770988] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EA14B348-B7C0-4A23-9984-3BE67FDBC,A34:7","pleaseConnect":0}]
2016-04-07 21:57:20.804 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:20.805 ThaliTest[2984:5771138] client: server will connect
2016-04-07 21:57:20.805 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 21:57:20.805 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:20.853 ThaliTest[2984:5770988] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E495FC9C:7","pleaseConnect":0}]
,2016-04-07 21:57:21.326 ThaliTest[2984:5770988] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D42275B6-6BF0-48D7-8A46-E91B6C0E6559:7","pleaseConnect":0}]
,2016-04-07 21:57:24.053 ThaliTest[2984:5771748] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:24.053 ThaliTest[2984:5771748] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:57:24.0,53 ThaliTest[2984:5771748] client session: disconnect
2016-04-07 21:57:24.053 ThaliTest[2984:5771748] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:24.053 ThaliTest[2984:5771748] client session: no connect callback (server initiated)
,2016-04-07 21:57:30.806 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-07 21:57:33.814 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:33.815 ThaliTest[2984:5771138] client: server will connect
2016-04-07 21:57:33.815 ThaliTest[2984:5771138] client session: reverseConn,ect
2016-04-07 21:57:33.815 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:34.021 ThaliTest[2984:5771747] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:34.022 ThaliTest[2984:5771747] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
,2016-04-07 21:57:34.022 ThaliTest[2984:5771747] client session: disconnect
,2016-04-07 21:57:34.022 ThaliTest[2984:5771747] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
,2016-04-07 21:57:34.023 ThaliTest[2984:5771747] client session: no connect callback (server initiated)
,2016-04-07 21:57:40.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:57:40.187 ThaliTest[2984:5770988] client: found updated peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:40.189 ThaliTest[2984:5770988] client: found updated peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8","pleaseConnect":0}]
2016-04-07 21:57:40.189 ThaliTest[2984:5770988] client: found updated peer: 2BA2C5EB-298D-4223-ADDC-0262E495,FC9C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{",peerAvailable":1,"peerIdentifier":"2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8","pleaseConnect":0}]
,2016-04-07 21:57:43.816 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 21:57:46.826 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:46.827 ThaliTest[2984:5771138] client: server will connect
2016-04-07 21:57:46.827 ThaliTest[2984:5771138] client session: reverseConn,ect
2016-04-07 21:57:46.827 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:57:47.253 ThaliTest[2984:5771873] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:47.253 ThaliTest[2984:5771873] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:57:47.2,53 ThaliTest[2984:5771873] client session: disconnect
,2016-04-07 21:57:47.253 ThaliTest[2984:5771873] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:57:47.255 ThaliTest[2984:5771873] client session: no connect callback (server initiated)
,2016-04-07 21:57:56.828 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 21:57:59.831 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:57:59.832 ThaliTest[2984:5771138] client: server will connect
2016-04-07 21:57:59.832 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 21:57:59.832 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:58:00.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:58:00.183 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:00.183 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:00.18,4 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:09.833 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 21:58:12.836 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:12.836 ThaliTest[2984:5771138] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:12.836 ThaliTest[2984:5771138] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 21:58:15.849 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:15.849 ThaliTest[2984:5771138] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:15.850 Thali,Test[2984:5771138] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 21:58:18.856 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:18.856 ThaliTest[2984:5771138] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:18.856 Thali,Test[2984:5771138] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 21:58:20.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:58:20.179 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:20.179 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:20.179 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:58:21.869 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:21.869 ThaliTest[2984:5771138] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:21.869 ThaliTest[2984:5771138] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 21:58:24.874 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:24.874 ThaliTest[2984:5771138] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:24.874 Thali,Test[2984:5771138] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 21:58:27.881 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:27.881 ThaliTest[2984:5771138] client: already connect(ing/ed) to EA14B348-B7C0-4A23-9984-3BE67FDBCA34:7
2016-04-07 21:58:27.882 ThaliTest[2984:5771138] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-07 21:58:32.834 ThaliTest[2984:5771990] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:32.834 ThaliTest[2984:5771990] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 21:58:32.8,34 ThaliTest[2984:5771990] client session: disconnect
2016-04-07 21:58:32.834 ThaliTest[2984:5771990] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:32.834 ThaliTest[2984:5771990] client session: no connect callback (server initiated)
,2016-04-07 21:58:40.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:58:40.180 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:58:40.180 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:58:40.18,0 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:59:00.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:59:00.180 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 21:59:00.183 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 21:59:00.183 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:20.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:59:20.181 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:59:20.182 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 21:59:20.182 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 21:59:40.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 21:59:40.180 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 21:59:40.180 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 21:59:40.184 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:00.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:00:00.181 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:00.181 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 22:00:00.186 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:20.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:00:20.179 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 22:00:20.179 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:20.17,9 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
,2016-04-07 22:00:40.166 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:00:40.178 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
2016-04-07 22:00:40.180 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:40.180 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
,2016-04-07 22:00:41.749 ThaliTest[2984:5771138] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-07 22:00:41.749 ThaliTest[2984:577113,8] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
2016-04-07 22:00:41.750 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening
2016-04-07 22:00:41.750 ThaliTest[2984:577113,8] THEMultipeerManager stopping peer
2016-04-07 22:00:41.750 ThaliTest[2984:5771138] multipeer manager: stop client timer
2016-04-07 22:00:41.751 ThaliTest[2984:5771138] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-07 22:00:55.544 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndListening
2016-04-07 22:00:55.545 ThaliTest[2984:5771138] server: starting 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:00:55.545 ThaliTest[2984:5771138] multipeer m,anager: start client restart timer: 0x15dbc4c0
2016-04-07 22:00:55.545 ThaliTest[2984:5771138] THEMultipeerManager initialized peer 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9
2016-04-07 22:00:55.545 ThaliTest[2984:5771138] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-07 22:00:55.548 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-07 22:00:55.548 ThaliTest[2984:5771138] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-07 22:00:56.855 ThaliTest[2984:5770988] client: found new peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:56.856 ThaliTest[2984:5770988] client: lost peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:00:56.856 ThaliTest[2984:,5770988] client session: onPeerLost: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:00:56.857 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:56.858 ThaliTest[2984:5771138] client: connect: unreachable ,EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:00:56.858 ThaliTest[2984:5771138] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative: Connect returned an error: Peer unreachable
INFO testThaliMobileNative: Scheduling a connect retry -, retries left: 9
,2016-04-07 22:00:57.531 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:00:57.532 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:00:57.752 ThaliTest[2984:5770988] client: found new peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:8
2016-04-07 22:00:57.752 ThaliTest[2984:5770988] client: found new peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:8
,2016-04-07 22:00:58.859 ThaliTest[2984:5770988] client: found updated peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:00:59.866 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:00:59.866 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:00:59.867 ThaliTest[2984:5771138] client session: reverseConn,ect
2016-04-07 22:00:59.867 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:00.044 ThaliTest[2984:5772327] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:00.044 ThaliTest[2984:5772327] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:01:00.046 ThaliTest[2984:5772327] client session: disconnect
2016-04-07 22:01:00.046 ThaliTest[2984:5772327] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:00.046 ThaliTest[2984:5772327] client session: no connect callb,ack (server initiated)
,2016-04-07 22:01:08.937 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:01:08.937 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:01:08.937 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:01:09.868 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-07 22:01:12.871 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:01:12.871 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:01:12.872 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:01:12.872 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:13.190 ThaliTest[2984:5772327] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:13.191 ThaliTest[2984:5772327] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:01:13.1,91 ThaliTest[2984:5772327] client session: disconnect
2016-04-07 22:01:13.191 ThaliTest[2984:5772327] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:13.191 ThaliTest[2984:5772327] client session: no connect callback (server initiated)
,2016-04-07 22:01:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:01:15.559 ThaliTest[2984:5770988] client: found updated peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:15.559 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:15.559 ThaliTest[2984:5770988] client: found updated peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:01:22.042 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:01:22.043 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:01:22.043 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:01:22.873 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-07 22:01:25.883 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:01:25.884 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:01:25.884 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:01:25.884 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:26.298 ThaliTest[2984:5772434] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:26.298 ThaliTest[2984:5772434] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:01:26.2,98 ThaliTest[2984:5772434] client session: disconnect
2016-04-07 22:01:26.299 ThaliTest[2984:5772434] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:26.299 ThaliTest[2984:5772434] client session: no connect callback (server initiated)
,2016-04-07 22:01:35.182 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:01:35.183 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:01:35.183 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:01:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:01:35.559 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:35.559 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:35.559 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:35.885 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-07 22:01:38.893 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:01:38.893 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:01:38.894 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:01:38.894 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:39.390 ThaliTest[2984:5772478] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:39.390 ThaliTest[2984:5772478] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:01:39.3,90 ThaliTest[2984:5772478] client session: disconnect
2016-04-07 22:01:39.390 ThaliTest[2984:5772478] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:39.391 ThaliTest[2984:5772478] client session: no connect callb,ack (server initiated)
,2016-04-07 22:01:47.849 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:01:47.850 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:01:47.850 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:01:48.895 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-07 22:01:51.901 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:01:51.902 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:01:51.902 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:01:51.902 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:01:52.893 ThaliTest[2984:5772477] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:52.895 ThaliTest[2984:5772477] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:01:52.8,95 ThaliTest[2984:5772477] client session: disconnect
2016-04-07 22:01:52.895 ThaliTest[2984:5772477] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:01:52.895 ThaliTest[2984:5772477] client session: no connect callback (server initiated)
,2016-04-07 22:01:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:01:55.567 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:01:55.568 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:01:55.568 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:00.892 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:02:00.892 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:02:00.892 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:02:01.903 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-07 22:02:04.914 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:02:04.914 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:02:04.915 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:02:04.915 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:05.608 ThaliTest[2984:5772366] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:05.609 ThaliTest[2984:5772366] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
,2016-04-07 22:02:05.609 ThaliTest[2984:5772366] client session: disconnect
,2016-04-07 22:02:05.610 ThaliTest[2984:5772366] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:05.611 ThaliTest[2984:5772366] client session: no connect callback (server initiated)
,2016-04-07 22:02:14.376 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:02:14.376 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:02:14.376 ThaliTest[2984:5770988], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:02:14.916 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-07 22:02:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:02:15.561 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:02:15.563 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:15.563 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:02:17.923 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:02:17.924 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:02:17.924 ThaliTest[2984:5771138] client session: reverseConn,ect
2016-04-07 22:02:17.924 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:18.180 ThaliTest[2984:5772600] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:18.180 ThaliTest[2984:5772600] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:02:18.181 ThaliTest[2984:5772600] client session: disconnect
,2016-04-07 22:02:18.181 ThaliTest[2984:5772600] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:18.182 ThaliTest[2984:5772600] client session: no connect callback (server initiated)
,2016-04-07 22:02:27.142 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:02:27.142 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:02:27.142 ThaliTest[2984:5770988], server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:02:27.925 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-07 22:02:30.929 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:02:30.929 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:02:30.929 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:02:30.929 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:31.609 ThaliTest[2984:5772478] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:31.610 ThaliTest[2984:5772478] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:02:31.6,10 ThaliTest[2984:5772478] client session: disconnect
2016-04-07 22:02:31.610 ThaliTest[2984:5772478] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:31.611 ThaliTest[2984:5772478] client session: no connect callback (server initiated)
,2016-04-07 22:02:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:02:35.574 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:02:35.576 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:02:35.578 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:40.196 ThaliTest[2984:5770988] multipeer session: reset timer
2016-04-07 22:02:40.196 ThaliTest[2984:5770988] server: disconnecting to refresh session (2BA2C5EB-298D-4223-ADDC-0262E495FC9C)
2016-04-07 22:02:40.196 ThaliTest[2984:5770988] server: rejecting invitation from 2BA2C5EB-298D-4223-ADDC-0262E495FC9C due to previous generation (7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:9 != 7CE54148-3BE3-4CB1-B795-F4E22EFFEFEE:8)
,2016-04-07 22:02:40.930 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-07 22:02:43.944 ThaliTest[2984:5771138] jxcore: connect EA14B348-B7C0-4A23-9984-3BE67FDBCA34:8
2016-04-07 22:02:43.944 ThaliTest[2984:5771138] client: server will connect
2016-04-07 22:02:43.944 ThaliTest[2984:5771138] client session: reverseConnect
2016-04-07 22:02:43.944 ThaliTest[2984:5771138] client session: stateChange:0->1 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:02:44.420 ThaliTest[2984:5772478] client session: not connected EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:44.420 ThaliTest[2984:5772478] client session: onLinkFailure: EA14B348-B7C0-4A23-9984-3BE67FDBCA34
2016-04-07 22:02:44.4,20 ThaliTest[2984:5772478] client session: disconnect
2016-04-07 22:02:44.420 ThaliTest[2984:5772478] client session: stateChange:1->0 EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:44.420 ThaliTest[2984:5772478] client session: no connect callback (server initiated)
,2016-04-07 22:02:53.945 ThaliTest[2984:5770988] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-07 22:02:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:02:55.560 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:02:55.560 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:02:55.56,0 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:03:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:03:15.561 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:15.561 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:03:15.564 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:03:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:03:35.563 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:35.564 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:03:35.568 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:03:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:03:55.573 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:03:55.573 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:03:55.573 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:04:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:04:15.563 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:15.565 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:15.565 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:04:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:04:35.571 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:04:35.571 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:04:35.572 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:04:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:04:55.564 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:04:55.564 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:04:55.56,4 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:05:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:05:15.561 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:05:15.561 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:05:15.563 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:05:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:05:35.562 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:05:35.562 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:05:35.563 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:05:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:05:55.576 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:05:55.576 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:05:55.57,6 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:06:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:06:15.570 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:06:15.571 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:15.573 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:06:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:06:35.562 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:06:35.563 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:35.564 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:06:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:06:55.564 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:06:55.564 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:06:55.56,5 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:07:15.572 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:07:15.573 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:15.573 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:07:35.573 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:35.574 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:07:35.575 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:07:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:07:55.563 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:07:55.563 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:07:55.563 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:08:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:08:15.570 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:15.571 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:08:15.573 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:08:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:08:35.572 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:35.573 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:08:35.57,3 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:08:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:08:55.580 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:08:55.580 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:08:55.581 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:09:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:09:15.563 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:09:15.565 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:09:15.565 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:09:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:09:35.573 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:09:35.573 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:09:35.574 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:09:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:09:55.562 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:09:55.563 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
2016-04-07 22:09:55.563 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:10:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:10:15.563 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:10:15.564 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:15.56,4 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:10:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:10:35.571 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:10:35.572 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:35.57,3 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:10:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:10:55.562 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:10:55.562 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:10:55.563 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:11:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:11:15.583 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:11:15.584 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:15.584 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:11:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:11:35.571 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:11:35.571 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:35.57,1 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:11:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:11:55.569 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:11:55.570 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:11:55.573 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:12:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:12:15.560 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:15.561 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
,2016-04-07 22:12:15.564 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:12:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:12:35.559 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:35.559 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:35.56,0 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:12:55.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:12:55.576 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:12:55.576 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:12:55.578 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:13:15.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:13:15.560 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:13:15.561 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
,2016-04-07 22:13:15.564 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9
,2016-04-07 22:13:35.546 ThaliTest[2984:5770988] multipeer manager: restart client
,2016-04-07 22:13:35.570 ThaliTest[2984:5770988] client: found existing peer: D42275B6-6BF0-48D7-8A46-E91B6C0E6559:9
2016-04-07 22:13:35.570 ThaliTest[2984:5770988] client: found existing peer: 2BA2C5EB-298D-4223-ADDC-0262E495FC9C:9
2016-04-07 22:13:35.570 ThaliTest[2984:5770988] client: found existing peer: EA14B348-B7C0-4A23-9984-3BE67FDBCA34:9

```
