#### Test 64531254841497d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8C705C51-1141-46A2-B147-F2A4F48413DA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8C705C51-1141-46A2-B147-F2A4F48413DA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64531254841497d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56567"
,(lldb)     command script import "/tmp/8C705C51-1141-46A2-B147-F2A4F48413DA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 23:40:19.812 ThaliTest[2457:4492520] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/98C7DC2A-30EC-43FE-B0D4-022F8FE5012F/Library/Cookies/Cookies.binarycookies
,2016-03-29 23:40:20.070 ThaliTest[2457:4492520] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 23:40:20.071 ThaliTest[2457:4492520] Multi-tasking -> Device: YES, App: YES
,2016-03-29 23:40:20.090 ThaliTest[2457:4492520] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 23:40:20.907 ThaliTest[2457:4492520] Using UIWebView
,2016-03-29 23:40:20.910 ThaliTest[2457:4492520] [CDVTimer][handleopenurl] 0.160992ms
,2016-03-29 23:40:20.913 ThaliTest[2457:4492520] [CDVTimer][intentandnavigationfilter] 2.830982ms
2016-03-29 23:40:20.913 ThaliTest[2457:4492520] [CDVTimer][gesturehandler] 0.135005ms
2016-03-29 23:40:20.914 ThaliTest[2457:4492520] [CDVTimer][TotalPluginS,tartup] 3.814995ms
,2016-03-29 23:40:24.183 ThaliTest[2457:4492520] Resetting plugins due to page load.
,2016-03-29 23:40:25.670 ThaliTest[2457:4492520] Finished load of: file:///var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/index.html
,2016-03-29 23:40:25.856 ThaliTest[2457:4492520] JXcore Cordova plugin initializing
,2016-03-29 23:40:25.942 ThaliTest[2457:4492691] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-29 23:40:34.159 ThaliTest[2457:4492691] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 23:40:34.160 ThaliTest[2457:4492691] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 23:40:34.160 ThaliTest[2457:4,492691] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 23:40:34.163 ThaliTest[2457:4492691] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1F3648F6-21E2-45AD-ACF9-A7C951F27289/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55421
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55423
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
DEBUG createNativeListener: listening 55426
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55430
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 55435
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55439
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
DEBUG createNativeListener: listening 55443
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 55447
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
ok 26 The mux object should be closed,
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55451
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
DEBUG createNativeListener: listening 55503
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
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
DEBUG createNativeListener: listening 55507
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
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
# teardown
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
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 own UUID is found from the participants list
# teardow,n
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
,# teardown
,ok 84 error should be null
ok 85 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
,# teardown
,ok 87 error should be null
ok 88 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55517
,2016-03-29 23:43:11.915 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:43:11.916 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 89 error should be null
,ok 90 error should be null
,2016-03-29 23:43:11.919 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 23:43:11.920 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,# teardown
,2016-03-29 23:43:12.062 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:12.062 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
,2016-03-29 23:43:12.062 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:12.063 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:12.064 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55519
,2016-03-29 23:43:12.315 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
,2016-03-29 23:43:12.317 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 23:43:12.319 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,2016-03-29 23:43:12.453 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-29 23:43:12.455 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,# teardown
,2016-03-29 23:43:12.681 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:12.682 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:12.682 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:12.682 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
2016-03-29 23:43:12.682 ThaliTest[2457:4492691] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:12.683 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55521
,2016-03-29 23:43:13.212 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:13.212 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:1
2016-03-29 23:43:13.212 ThaliTest[2457:4492691] multipeer m,anager: start client restart timer: 0x16ec3ca0
2016-03-29 23:43:13.213 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:1
2016-03-29 23:43:13.213 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 23:43:13.224 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:13.224 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:13.224 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:43:13.225 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:2
,2016-03-29 23:43:13.225 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
2016-03-29 23:43:13.230 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:2
2016-03-29 23:43:13.230 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
# teardown
,2016-03-29 23:43:14.530 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:2
,2016-03-29 23:43:16.297 ThaliTest[2457:4492520] client: lost peer: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:43:16.297 ThaliTest[2457:4492520] client session: onPeerLost: E4612A32-7792-490E-A387-1EC57335E3B6
,2016-03-29 23:43:21.370 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:21.370 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:21.371 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:43:21.371 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
2016-03-29 23:43:21.371 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:21.372 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55526
2016-03-29 23:43:33.514 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:33.514 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:33.514 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
,2016-03-29 23:43:33.518 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:33.518 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:33.518 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-29 23:43:42.549 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:42.549 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:42.549 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:42.549 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:42.550 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55528
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-29 23:43:42.973 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:42.974 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:42.974 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:42.974 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:42.975 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55530
2016-03-29 23:43:43.259 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
2016-03-29 23:43:43.259 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:43:43.260 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success,
,2016-03-29 23:43:43.291 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:43:43.291 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:3
2016-03-29 23:43:43.291 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:3
2016-03-29 23:43:43.292 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-29 23:43:43.669 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:43:43.669 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:43:43.670 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 23:43:43.670 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
2016-03-29 23:43:43.670 ThaliTest[2457:4492691] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:43:43.671 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
,# 31. does not send duplicate availability changes
,ok 123 should be called once
,ok 124 should not have been called more than once
# teardown
,ok 125 error should be null
ok 126 error should be null
,# setup
,# 32. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
ok 131 port should match
,ok 132 host address should be null
ok 133 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
,ok 135 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-03-29 23:44:25.307 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
2016-03-29 23:44:25.307 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:25.308 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 23:44:25.308 ThaliTes,t[2457:4492691] jxcore: stopListeningForAdvertisements
2016-03-29 23:44:25.309 ThaliTest[2457:4492691] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:25.309 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 23:44:26.087 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:26.088 ThaliTest[2457:44926,91] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:26.089 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:26.089 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:44:26.089 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 23:44:29.421 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
2016-03-29 23:44:29.421 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:29.422 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 23:44:29.423 ThaliTes,t[2457:4492691] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:44:29.424 ThaliTest[2457:4492691] jxcore: startListeningForAdv,ertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 23:44:45.691 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
2016-03-29 23:44:45.692 ThaliTest[2457:4492691] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-29 23:44:45.692 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:45.693 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:45.693 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:44:45.693 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-03-29 23:44:54.079 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.080 ThaliTest[2457:44926,91] jxcore: stopListeningForAdvertisements: success
ok 144 Can call stopListeningForAdvertisements without error
2016-03-29 23:44:54.080 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:54.081 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 145 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 23:44:57.104 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:44:57.105 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:44:57.105 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:44:57.105 ThaliTest[2457:44926,91] THEMultipeerManager stopping peer
2016-03-29 23:44:57.105 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-29 23:45:03.213 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:03.214 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:4
2016-03-29 23:45:03.214 ThaliTest[2457:4492691] multipeer m,anager: start client restart timer: 0x16ec3ca0
2016-03-29 23:45:03.214 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:4
2016-03-29 23:45:03.214 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:03.215 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:03.215 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
,2016-03-29 23:45:03.215 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:45:03.219 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 149 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-29 23:45:03.596 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:45:03.597 ThaliTest[2457:44926,91] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:03.598 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:03.598 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:45:03.598 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-29 23:45:06.506 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:06.506 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:5
2016-03-29 23:45:06.507 ThaliTest[2457:4492691] multipeer m,anager: start client restart timer: 0x16ec3ca0
2016-03-29 23:45:06.507 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:5
2016-03-29 23:45:06.507 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 152 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:06.508 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:45:06.508 ThaliTest[2457:4492691] THEMultipeerManager stopping pee,r
2016-03-29 23:45:06.508 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:45:06.509 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:6
2016-03-29 23:45:06.509 ThaliTest[2457:4492691] multipeer mana,ger: start client restart timer: 0x16ec3ca0
2016-03-29 23:45:06.510 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:6
2016-03-29 23:45:06.510 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListe,ning: success
ok 153 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,1] THEMultipeerManager stopping peer
2016-03-29 23:45:07.840 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:45:07.841 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 155 Should be able to call stopAdve2016-03-29 23:45:07.838 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:45:07.839 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 154 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:07.840 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:07.840 ThaliTest[2457:449269,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-03-29 23:45:59.329 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:59.330 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:45:59.330 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 156 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:45:59.330 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:59.331 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:45,:59.331 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 157 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-29 23:45:59.489 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:45:59.490 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:45:59.490 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:45:59.490 ThaliTest[2457:44926,91] THEMultipeerManager stopping peer
2016-03-29 23:45:59.490 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-03-29 23:46:00.009 ThaliTest[2457:4492691] jxcore: connect foo
2016-03-29 23:46:00.009 ThaliTest[2457:4492691] jxcore: connect: fail: Start browsing first
not ok 160 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvert,isements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-03-29 23:46:00.161 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 23:46:00.162 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 161 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:46:00.163 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:46:00.163 ThaliTest[2457:44926,91] THEMultipeerManager stopping peer
2016-03-29 23:46:00.163 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-03-29 23:46:00.492 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:46:00.493 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:7
2016-03-29 23:46:00.493 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
2016-03-29 23:46:00.493 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:7
2016-03-29 23:46:00.493 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-29 23:46:00.494 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-29 23:46:00.495 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-29 23:46:01.650 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:7
ok 165 peers must be an array
ok 166 peers must not be zero-length
ok 167 peer must have peerIdentifier
ok 168 peerIdentifier must be a strin,g
ok 169 peer must have peerAvailable
ok 170 peer must have pleaseConnect
,# teardown
,2016-03-29 23:46:02.172 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:03.388 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:46:03.389 ThaliTest[2457:449269,1] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:46:03.389 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:46:03.390 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:46:03.390 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:46:03.390 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-03-29 23:46:05.754 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:46:05.754 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
2016-03-29 23:46:05.755 ThaliTest[2457:4492691] multipeer m,anager: start client restart timer: 0x16ec3ca0
2016-03-29 23:46:05.755 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:8
2016-03-29 23:46:05.755 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:46:05.756 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:46:05.756 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-29 23:46:05.770 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7","pleaseConnect":0}]
2016-03-29 23:46:05.772 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:05.772 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:05.772 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:06.335 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:7","pleaseConnect":0}]
,2016-03-29 23:46:06.900 ThaliTest[2457:4493476] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:06.901 ThaliTest[2457:4493476] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:46:06.901 ThaliTest[2457:4493476] client session: disconnect
2016-03-29 23:46:06.903 ThaliTest[2457:4493476] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:06.903 ThaliTest[2457:4493476] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:06.903 ThaliTest[2457:4493476] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:46:09.912 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:09.912 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:09.912 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:09.992 ThaliTest[2457:4493476] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:09.994 ThaliTest[2457:4493476] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:09.9,94 ThaliTest[2457:4493476] client session: disconnect
2016-03-29 23:46:09.994 ThaliTest[2457:4493476] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:09.995 ThaliTest[2457:4493476] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:09.995 ThaliTest[2457:4493476] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 8
,2016-03-29 23:46:12.999 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:12.999 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:12.999 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:13.190 ThaliTest[2457:4493475] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:13.190 ThaliTest[2457:4493475] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:13.1,91 ThaliTest[2457:4493475] client session: disconnect
2016-03-29 23:46:13.191 ThaliTest[2457:4493475] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:13.191 ThaliTest[2457:4493475] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:13.192 ThaliTest[2457:4493475] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:46:16.202 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:16.203 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:16.203 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:16.282 ThaliTest[2457:4493476] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:16.282 ThaliTest[2457:4493476] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:16.282 ThaliTest[2457:4493476] client session: disconnect
2016-03-29 23:46:16.282 ThaliTest[2457:4493476] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:16.284 ThaliTest[2457:4493476] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:46:16.284 ThaliTest[2457:4493476] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:46:19.292 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:19.292 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:19.292 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:19.483 ThaliTest[2457:4493475] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:19.484 ThaliTest[2457:4493475] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:19.4,84 ThaliTest[2457:4493475] client session: disconnect
2016-03-29 23:46:19.484 ThaliTest[2457:4493475] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:19.485 ThaliTest[2457:4493475] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:19.485 ThaliTest[2457:4493475] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:46:22.491 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:22.491 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:22.491 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:22.605 ThaliTest[2457:4493504] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:22.605 ThaliTest[2457:4493504] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:22.6,05 ThaliTest[2457:4493504] client session: disconnect
2016-03-29 23:46:22.605 ThaliTest[2457:4493504] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:22.605 ThaliTest[2457:4493504] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:22.605 ThaliTest[2457:4493504] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:46:25.620 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:25.620 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:25.620 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
,2016-03-29 23:46:25.732 ThaliTest[2457:4493476] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:25.732 ThaliTest[2457:4493476] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:25.7,32 ThaliTest[2457:4493476] client session: disconnect
2016-03-29 23:46:25.732 ThaliTest[2457:4493476] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:25.733 ThaliTest[2457:4493476] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:25.733 ThaliTest[2457:4493476] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:46:25.756 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:46:25.770 ThaliTest[2457:4492520] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:25.771 ThaliTest[2457:4492520] client: found updated peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier,":"E4612A32-7792-490E-A387-1EC57335E3B6:8","pleaseConnect":0}]
,2016-03-29 23:46:28.742 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:28.742 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:28.742 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:28.921 ThaliTest[2457:4493613] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:28.923 ThaliTest[2457:4493613] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:28.923 ThaliTest[2457:4493613] client session: disconnect
2016-03-29 23:46:28.923 ThaliTest[2457:4493613] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:28.923 ThaliTest[2457:4493613] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:28.923 ThaliTest[2457:4493613] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:46:31.934 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:31.935 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:31.935 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:32.009 ThaliTest[2457:4493503] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:32.009 ThaliTest[2457:4493503] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:32.009 ThaliTest[2457:4493503] client session: disconnect
2016-03-29 23:46:32.009 ThaliTest[2457:4493503] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:32.010 ThaliTest[2457:4493503] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:32.010 ThaliTest[2457:4493503] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:46:35.027 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:7
2016-03-29 23:46:35.027 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:46:35.027 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:46:35.147 ThaliTest[2457:4493503] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:35.148 ThaliTest[2457:4493503] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:46:35.148 ThaliTest[2457:4493503] client session: disconnect
,2016-03-29 23:46:35.149 ThaliTest[2457:4493503] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:35.150 ThaliTest[2457:4493503] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 2,3:46:35.150 ThaliTest[2457:4493503] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
,  ---
,    operator: fail
  ...
,# teardown
,2016-03-29 23:46:45.756 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:46:45.767 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:46:45.768 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:05.756 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:47:05.767 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:05.767 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:13.624 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:47:13.625 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 176 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:47:13.626 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:47:13.626 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:47:13.626 ThaliTest[2457:4492691] multipeer manager: stop client timer
20,16-03-29 23:47:13.626 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Can shift large amounts of data
,2016-03-29 23:47:15.197 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 23:47:15.198 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:47:15.204 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
,2016-03-29 23:47:15.206 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:9
,2016-03-29 23:47:15.206 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening: success
,ok 178 Can call startUpdateAdvertisingAndListening without error
,2016-03-29 23:47:15.208 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-29 23:47:15.210 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
,ok 179 Can call startListeningForAdvertisements without error
,2016-03-29 23:47:16.039 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:16.040 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:16.041 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:16.041 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:16.087 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:17.358 ThaliTest[2457:4493690] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:17.360 ThaliTest[2457:4493690] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:17.3,60 ThaliTest[2457:4493690] client session: disconnect
2016-03-29 23:47:17.360 ThaliTest[2457:4493690] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:17.361 ThaliTest[2457:4493690] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:17.361 ThaliTest[2457:4493690] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 9
,2016-03-29 23:47:20.369 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:20.370 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:20.370 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:22.231 ThaliTest[2457:4493736] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:22.232 ThaliTest[2457:4493736] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:22.232 ThaliTest[2457:4493736] client session: disconnect
2016-03-29 23:47:22.232 ThaliTest[2457:4493736] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:22.232 ThaliTest[2457:4493736] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:22.232 ThaliTest[2457:4493736] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:47:25.242 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:25.242 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:25.242 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:26.371 ThaliTest[2457:4493739] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:26.372 ThaliTest[2457:4493739] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:26.3,72 ThaliTest[2457:4493739] client session: disconnect
2016-03-29 23:47:26.372 ThaliTest[2457:4493739] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:26.373 ThaliTest[2457:4493739] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:26.373 ThaliTest[2457:4493739] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:47:29.381 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:29.381 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:29.382 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:29.607 ThaliTest[2457:4493736] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:29.608 ThaliTest[2457:4493736] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:29.609 ThaliTest[2457:4493736] client session: disconnect
2016-03-29 23:47:29.609 ThaliTest[2457:4493736] client session:, stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:29.609 ThaliTest[2457:4493736] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:29.609 ThaliTest[2457:4493736] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:47:32.617 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:32.618 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:32.618 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:32.829 ThaliTest[2457:4493503] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:32.830 ThaliTest[2457:4493503] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:32.8,30 ThaliTest[2457:4493503] client session: disconnect
2016-03-29 23:47:32.830 ThaliTest[2457:4493503] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
,2016-03-29 23:47:32.831 ThaliTest[2457:4493503] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:32.831 ThaliTest[2457:4493503] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:47:35.207 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:47:35.220 ThaliTest[2457:4492520] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:35.220 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:47:35.839 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:35.840 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:35.840 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:35.993 ThaliTest[2457:4493739] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:35.994 ThaliTest[2457:4493739] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:35.994 ThaliTest[2457:4493739] client session: disconnect
2016-03-29 23:47:35.994 ThaliTest[2457:4493739] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:35.994 ThaliTest[2457:4493739] client session: fireConnectCallb,ack: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:35.994 ThaliTest[2457:4493739] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:47:39.004 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:39.004 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:39.005 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:39.213 ThaliTest[2457:4493736] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:39.213 ThaliTest[2457:4493736] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:39.213 ThaliTest[2457:4493736] client session: disconnect
2016-03-29 23:47:39.213 ThaliTest[2457:4493736] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:39.216 ThaliTest[2457:4493736] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:39.216 ThaliTest[2457:4493736] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:47:42.225 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:42.226 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:42.226 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:42.292 ThaliTest[2457:4493739] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:42.292 ThaliTest[2457:4493739] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:42.293 ThaliTest[2457:4493739] client session: disconnect
2016-03-29 23:47:42.293 ThaliTest[2457:4493739] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:42.294 ThaliTest[2457:4493739] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:42.294 ThaliTest[2457:4493739] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:47:45.301 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:45.302 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:45.302 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:45.441 ThaliTest[2457:4493503] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:45.441 ThaliTest[2457:4493503] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:47:45.441 ThaliTest[2457:4493503] client session: disconnect
,2016-03-29 23:47:45.442 ThaliTest[2457:4493503] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:45.443 ThaliTest[2457:4493503] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:45.444 ThaliTest[2457:4493503] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:47:48.451 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:8
2016-03-29 23:47:48.452 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:47:48.452 ThaliTest[2457:4492691] client session: stateChange:0->,1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:48.535 ThaliTest[2457:4493691] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:48.535 ThaliTest[2457:4493691] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:48.536 ThaliTest[2457:4493691] client session: disconnect
,2016-03-29 23:47:48.536 ThaliTest[2457:4493691] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
2016-03-29 23:47:48.537 ThaliTest[2457:4493691] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:47:48.537 ThaliTest[2457:4493691] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 180 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 23:47:55.207 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:47:55.219 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:47:55.221 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:15.206 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:48:15.216 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
,2016-03-29 23:48:15.220 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:24.579 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 23:48:24.580 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 181 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:48:24.582 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:48:24.582 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:48:24.582 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:48:24.582 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 182 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 44. #startUpdateAdvertisingAndListening - killing remote peers connection kills the local connection
,2016-03-29 23:48:24.975 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:48:24.976 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
2016-03-29 23:48:24.976 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
2016-03-29 23:48:24.976 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:10
2016-03-29 23:48:24.976 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 183 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:48:24.977 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertis,ingActive":true,"discoveryActive":true}
2016-03-29 23:48:24.978 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 184 Can call startListeningForAdvertisements without error
,2016-03-29 23:48:25.698 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:25.698 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:8","pleaseConnect":0}]
2016-03-29 23:48:25.700 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 2,3:48:25.700 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:48:25.700 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:48:25.700 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC573,35E3B6:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:9","pleaseConnect":0}]
,2016-03-29 23:48:26.525 ThaliTest[2457:4493691] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:26.525 ThaliTest[2457:4493691] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:48:26.525 ThaliTest[2457:4493691] client session: disconnect
2016-03-29 23:48:26.525 ThaliTest[2457:4493691] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:26.526 ThaliTest[2457:4493691] client session: no connect callback (server initiated)
,2016-03-29 23:48:35.701 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:48:38.704 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:38.704 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:48:38.705 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:48:38.705 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:8
,2016-03-29 23:48:39.542 ThaliTest[2457:4493989] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:39.544 ThaliTest[2457:4493989] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:48:39.544 ThaliTest[2457:4493989] client session: disconnect
2016-03-29 23:48:39.544 ThaliTest[2457:4493989] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:39.544 ThaliTest[2457:4493989] client session: no connect callback (server initiated)
,2016-03-29 23:48:44.977 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:48:44.989 ThaliTest[2457:4492520] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:48:44.990 ThaliTest[2457:4492520] client: found updated peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:10","pleaseConnect":0}]
,2016-03-29 23:48:48.706 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:48:51.714 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:48:51.714 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:48:51.715 ThaliTest[2457:4492691] client session: reverseConn,ect
2016-03-29 23:48:51.715 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:48:52.143 ThaliTest[2457:4493980] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:48:52.144 ThaliTest[2457:4493980] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:48:52.144 ThaliTest[2457:4493980] client session: disconnect
,2016-03-29 23:48:52.144 ThaliTest[2457:4493980] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:48:52.145 ThaliTest[2457:4493980] client session: no connect callback (server initiated)
,2016-03-29 23:49:01.716 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:49:04.726 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:04.726 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:49:04.727 ThaliTest[2457:4492691] client session: reverseConn,ect
2016-03-29 23:49:04.727 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:49:04.977 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:49:04.992 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:04.992 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:49:14.728 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:49:17.734 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:17.734 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:17.735 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:49:20.742 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:20.742 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:20.742 Thali,Test[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:49:23.754 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:23.754 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:23.754 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:49:24.977 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:49:24.989 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
2016-03-29 23:49:24.989 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:49:26.761 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:26.761 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:26.761 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:49:29.772 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:29.772 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:29.772 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:49:32.777 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:32.777 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:8
2016-03-29 23:49:32.777 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 185 Connect failed
  ---
,    operator: fail
  ...
,# teardown
,2016-03-29 23:49:33.402 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:49:33.403 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 186 Should be able to call stopListeningForAdvertisements in teardown
2016-03-29 23:49:33.404 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
,2016-03-29 23:49:33.405 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:49:33.405 ThaliTest[2457:4492691] client session: disconnect
2016-03-29 23:49:33.405 ThaliTest[2457:4492691] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:33.405 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:49:33.406 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 187 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 45. #startUpdateAdvertisingAndListening - killing the local connection kills the connection to the remote peer
,2016-03-29 23:49:38.456 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:49:38.456 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
2016-03-29 23:49:38.456 ThaliTest[2457:4492691] multipeer ,manager: start client restart timer: 0x16ec3ca0
2016-03-29 23:49:38.457 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:11
2016-03-29 23:49:38.457 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAnd,Listening: success
ok 188 Can call startUpdateAdvertisingAndListening without error
,2016-03-29 23:49:38.458 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:49:38.459 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 189 Can call startListeningForAdvertisements without error
,2016-03-29 23:49:39.950 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:39.950 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:10","pleaseConnect":0}]
,2016-03-29 23:49:39.958 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:39.959 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:49:39.959 ThaliTest[2457:4492691] client session: reverseCon,nect
2016-03-29 23:49:39.959 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:10","pleaseConnect":0}]
,2016-03-29 23:49:42.825 ThaliTest[2457:4494045] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:42.825 ThaliTest[2457:4494045] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:49:42.,825 ThaliTest[2457:4494045] client session: disconnect
2016-03-29 23:49:42.826 ThaliTest[2457:4494045] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:42.826 ThaliTest[2457:4494045] client session: no connect callback (server initiated)
,2016-03-29 23:49:49.960 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:49:52.962 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:52.962 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:49:52.963 ThaliTest[2457:4492691] client session: reverseCon,nect
2016-03-29 23:49:52.963 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:49:54.537 ThaliTest[2457:4494186] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:54.537 ThaliTest[2457:4494186] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:49:54.537 ThaliTest[2457:4494186] client session: disconnect
2016-03-29 23:49:54.537 ThaliTest[2457:4494186] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:49:54.538 ThaliTest[2457:4494186] client session: no connect callback (server initiated)
,2016-03-29 23:49:58.458 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:49:58.470 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:49:58.472 ThaliTest[2457:4492520] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F367,2D83BC4F:11","pleaseConnect":0}]
,2016-03-29 23:50:02.964 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:50:05.967 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:05.967 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:50:05.967 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:50:05.968 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:06.448 ThaliTest[2457:4494186] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:06.448 ThaliTest[2457:4494186] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:50:06.448 ThaliTest[2457:4494186] client session: disconnect
,2016-03-29 23:50:06.448 ThaliTest[2457:4494186] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:06.450 ThaliTest[2457:4494186] client session: no connect callback (server initiated)
,2016-03-29 23:50:15.969 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:50:18.457 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:50:18.468 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:18.469 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:50:18.972 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:18.972 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:50:18.972 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:50:18.972 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:19.621 ThaliTest[2457:4494307] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:19.622 ThaliTest[2457:4494307] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:50:19.623 ThaliTest[2457:4494307] client session: disconnect
2016-03-29 23:50:19.623 ThaliTest[2457:4494307] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:19.623 ThaliTest[2457:4494307] client session: no connect callback (server initiated)
,2016-03-29 23:50:28.973 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:50:31.979 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:31.979 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:50:31.980 ThaliTest[2457:4492691] client session: reverseCon,nect
2016-03-29 23:50:31.980 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:32.656 ThaliTest[2457:4494186] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:32.656 ThaliTest[2457:4494186] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:50:32.,656 ThaliTest[2457:4494186] client session: disconnect
2016-03-29 23:50:32.656 ThaliTest[2457:4494186] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:32.656 ThaliTest[2457:4494186] client session: no connect callback (server initiated)
,2016-03-29 23:50:38.458 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:50:38.471 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:50:38.471 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:41.981 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:50:44.994 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:44.994 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:50:44.995 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:50:44.995 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:45.959 ThaliTest[2457:4494186] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:45.960 ThaliTest[2457:4494186] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:50:45.,960 ThaliTest[2457:4494186] client session: disconnect
2016-03-29 23:50:45.960 ThaliTest[2457:4494186] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:45.960 ThaliTest[2457:4494186] client session: no connect callback (server initiated)
,2016-03-29 23:50:54.996 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:50:57.998 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:57.998 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:50:57.999 ThaliTest[2457:4492691] client session: reverseCon,nect
2016-03-29 23:50:57.999 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:50:58.458 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:50:58.470 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:50:58.471 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:08.000 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:51:11.011 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:11.011 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:11.011 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:51:14.024 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:14.024 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:14.025 Tha,liTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:51:17.032 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:17.032 ThaliTest[2457:4492691] client: already connect(ing/ed) to E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:17.033 Tha,liTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 190 Connect failed
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 23:51:17.504 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 23:51:17.506 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
ok 191 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:51:17.507 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:51:17.507 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:51:17.507 ThaliTest[2457:4492691] client session: disconnect
2016-03-29 2,3:51:17.507 ThaliTest[2457:4492691] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:17.508 ThaliTest[2457:4492691] multipeer manager: stop client timer
2016-03-29 23:51:17.508 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 192 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 46. We do not emit peerAvailabilityChanged events until one of the start methods is called
,2016-03-29 23:51:19.962 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
2016-03-29 23:51:19.963 ThaliTest[2457:4492691] multipeer manager: start client restart timer: 0x16ec3ca0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 23:51:19.964 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 193 We should start listening fine
2016-03-29 23:51:19.965 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:51:19.965 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
,2016-03-29 23:51:19.966 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12
2016-03-29 23:51:19.966 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening: success
ok 194 We should start updating fine
# teardown
,2016-03-29 23:51:19.979 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:19.980 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"E4612A32-7792-490E-A387-1EC57335E3B6:10","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11","pleaseConnect":0}]
,2016-03-29 23:51:26.036 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 23:51:26.037 ThaliTest[2457:4492691] jxcore: stopListeningForAdvertisements: success
,ok 195 Should be able to call stopListeningForAdvertisements in teardown
,2016-03-29 23:51:26.039 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening
2016-03-29 23:51:26.039 ThaliTest[2457:4492691] THEMultipeerManager stopping peer
2016-03-29 23:51:26.039 ThaliTest[2457:4492691] multipeer manager: stop client timer
20,16-03-29 23:51:26.039 ThaliTest[2457:4492691] jxcore: stopAdvertisingAndListening: success
ok 196 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 47. Test updating advertising and parallel data transfer
,2016-03-29 23:51:28.362 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening
2016-03-29 23:51:28.362 ThaliTest[2457:4492691] server: starting 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
2016-03-29 23:51:28.362 ThaliTest[2457:4492691] multipeer ,manager: start client restart timer: 0x16ec3ca0
2016-03-29 23:51:28.362 ThaliTest[2457:4492691] THEMultipeerManager initialized peer 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13
,2016-03-29 23:51:28.367 ThaliTest[2457:4492691] jxcore: startUpdateAdvertisingAndListening: success
ok 197 Can call startUpdateAdvertisingAndListening without error
2016-03-29 23:51:28.373 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 23:51:28.374 ThaliTest[2457:4492691] jxcore: startListeningForAdvertisements: success
ok 198 Can call startListeningForAdvertisements without error
,2016-03-29 23:51:29.203 ThaliTest[2457:4492520] client: found new peer: E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:29.203 ThaliTest[2457:4492520] client: found new peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:29.205 ThaliT,est[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:29.205 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:51:29.205 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:51:29.206 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:51:29.214 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:29.214 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:51:29.215 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:29.468 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:29.468 ThaliTest[2457:4492520] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:30.537 ThaliTest[2457:4494307] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:30.537 ThaliTest[2457:4494307] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:30.538 ThaliTest[2457:4494307] client session: disconnect
2016-03-29 23:51:30.539 ThaliTest[2457:4494307] client session:, stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:30.539 ThaliTest[2457:4494307] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:30.539 ThaliTest[2457:4494307] jxcore: connect: fail: Pee,r disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:51:30.706 ThaliTest[2457:4492520] multipeer session: reset timer
,2016-03-29 23:51:30.707 ThaliTest[2457:4492520] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:31.032 ThaliTest[2457:4494321] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:31.032 ThaliTest[2457:4494321] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
,2016-03-29 23:51:31.032 ThaliTest[2457:4494321] client session: disconnect
,2016-03-29 23:51:31.032 ThaliTest[2457:4494321] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:31.033 ThaliTest[2457:4494321] client session: no connect callback (server initiated)
,2016-03-29 23:51:33.544 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:33.544 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:51:33.544 ThaliTest[2457:4492691] client session: stateChange:0-,>1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:33.966 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:33.966 ThaliTest[2457:4492520] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:33.967 ThaliTest[2457:4492520] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:36.480 ThaliTest[2457:4494483] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:36.480 ThaliTest[2457:4494483] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:36.,480 ThaliTest[2457:4494483] client session: disconnect
2016-03-29 23:51:36.480 ThaliTest[2457:4494483] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:36.481 ThaliTest[2457:4494483] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:51:36.481 ThaliTest[2457:4494483] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 23:51:37.071 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:37.071 ThaliTest[2457:4492520] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:37.071 ThaliTest[2457:4492520], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:39.206 ThaliTest[2457:4492520] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 23:51:39.487 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:39.487 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:51:39.487 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:39.759 ThaliTest[2457:4494484] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:39.760 ThaliTest[2457:4494484] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:39.,761 ThaliTest[2457:4494484] client session: disconnect
2016-03-29 23:51:39.761 ThaliTest[2457:4494484] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:39.761 ThaliTest[2457:4494484] client session: fireConnectCal,lback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:39.761 ThaliTest[2457:4494484] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 23:51:40.218 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:40.218 ThaliTest[2457:4492520] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:40.218 ThaliTest[2457:4492520] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:42.210 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:42.210 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:51:42.210 ThaliTest[2457:4492691] client session: reverseConnect
2016-03-29 23:51:42.210 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:10
,2016-03-29 23:51:42.308 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:42.308 ThaliTest[2457:4492520] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:51:42.308 ThaliTest[2457:4492520] server: rejecting invitation from 7E69AB12-44FB-4D43-AD41-F3672D83BC4F due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:42.767 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:42.768 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:51:42.768 ThaliTest[2457:4492691] client session: stateChange:0-,>1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:42.838 ThaliTest[2457:4494307] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:42.838 ThaliTest[2457:4494307] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:51:42.838 ThaliTest[2457:4494307] client session: disconnect
2016-03-29 23:51:42.839 ThaliTest[2457:4494307] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:42.840 ThaliTest[2457:4494307] client ses,sion: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:42.840 ThaliTest[2457:4494307] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 23:51:43.420 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:43.420 ThaliTest[2457:4492520] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:43.420 ThaliTest[2457:4492520] server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:45.843 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:45.844 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:51:45.844 ThaliTest[2457:4492691] client session: stateChange:0-,>1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:45.904 ThaliTest[2457:4494307] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:45.904 ThaliTest[2457:4494307] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
,2016-03-29 23:51:45.905 ThaliTest[2457:4494307] client session: disconnect
2016-03-29 23:51:45.906 ThaliTest[2457:4494307] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:10
2016-03-29 23:51:45.906 ThaliTest[2457:4494307] client session: no connect callback (server initiated)
,2016-03-29 23:51:46.033 ThaliTest[2457:4494483] client session: not connected 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:46.034 ThaliTest[2457:4494483] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:46.034 ThaliTest[2457:4494483] client session: disconnect
,2016-03-29 23:51:46.034 ThaliTest[2457:4494483] client session: stateChange:1->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:46.035 ThaliTest[2457:4494483] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 ,23:51:46.035 ThaliTest[2457:4494483] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-29 23:51:46.503 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:46.503 ThaliTest[2457:4492520] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:46.503 ThaliTest[2457:4492520], server: rejecting invitation from E4612A32-7792-490E-A387-1EC57335E3B6 due to previous generation (7E75333B-5CA8-4BAB-BD6C-23036DBD2655:13 != 7E75333B-5CA8-4BAB-BD6C-23036DBD2655:12)
,2016-03-29 23:51:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:51:48.375 ThaliTest[2457:4492520] client: found updated peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:48.375 ThaliTest[2457:4492520] client: found updated peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:48.376 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:48.377 ThaliTest[2457:4492691] client session: connect
2016-03-29 23:51:48.377 ThaliTest[2457:4492691] client session: stateChange:0->1 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:51:48.385 ThaliTest[2457:4492691] jxcore: connect E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:48.386 ThaliTest[2457:4492691] client: server will connect
2016-03-29 23:51:48.386 ThaliTest[2457:4492691] client session: reverseCon,nect
2016-03-29 23:51:48.387 ThaliTest[2457:4492691] client session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:51:48.609 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:48.609 ThaliTest[2457:4492520] server: disconnecting to refresh session (7E69AB12-44FB-4D43-AD41-F3672D83BC4F)
2016-03-29 23:51:48.609 ThaliTest[2457:4492520] server: rejecting invitation for lexical ordering 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
,2016-03-29 23:51:48.661 ThaliTest[2457:4492520] multipeer session: reset timer
2016-03-29 23:51:48.661 ThaliTest[2457:4492520] server: disconnecting to refresh session (E4612A32-7792-490E-A387-1EC57335E3B6)
2016-03-29 23:51:48.662 ThaliTest[2457:4492520], server session: connect
2016-03-29 23:51:48.662 ThaliTest[2457:4492520] server session: stateChange:0->1 E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:51:48.666 ThaliTest[2457:4492520] server: accepting invitation E4612A32-7792-490E-A387-1EC57335E3B6
,2016-03-29 23:51:48.908 ThaliTest[2457:4494483] client session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:48.910 ThaliTest[2457:4494483] client session: onLinkFailure: E4612A32-7792-490E-A387-1EC57335E3B6
2016-03-29 23:51:48.910 ThaliTest[2457:4494483] client session: disconnect
2016-03-29 23:51:48.910 ThaliTest[2457:4494483] client session: stateChange:1->0 E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:51:48.910 ThaliTest[2457:4494483] client session: no connect callback (server initiated)
,2016-03-29 23:51:49.042 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:49.042 ThaliTest[2457:4492691] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
,2016-03-29 23:51:49.042 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 23:51:50.135 ThaliTest[2457:4494483] client session: p2p link connected
,2016-03-29 23:51:50.139 ThaliTest[2457:4494483] client session: stateChange:1->2 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:51:50.139 ThaliTest[2457:4494483] client session: fireConnectCallback: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:51:50.139 ThaliTest[2457:4494483] jxcore: connect: success
,2016-03-29 23:51:50.155 ThaliTest[2457:4492520] client: relay established
2016-03-29 23:51:50.155 ThaliTest[2457:4492520] client: new accepted socket: 0x1a076140
,2016-03-29 23:51:51.467 ThaliTest[2457:4494571] server session: p2p link connected
,2016-03-29 23:51:51.476 ThaliTest[2457:4492520] server relay: connected (to port: 55596)
2016-03-29 23:51:51.477 ThaliTest[2457:4492520] server session: stateChange:1->2 E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:51:51.477 ThaliTest[2457:4492520] jxcore: connect: success
,DEBUG testThaliMobileNative: Got recoverable client error Error: ListeningPort is 0
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,INFO testThaliMobileNative: got data
,2016-03-29 23:51:51.906 ThaliTest[2457:4492520] server relay: socket disconnected
2016-03-29 23:51:51.907 ThaliTest[2457:4492520] server relay: 0x1a0643d0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,ok 199 At least one should fire before we hit close
,2016-03-29 23:51:52.052 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:52.053 ThaliTest[2457:4492691] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:52.053 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 23:51:55.056 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:55.056 ThaliTest[2457:4492691] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:55.057 Tha,liTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 23:51:58.061 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:58.062 ThaliTest[2457:4492691] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:51:58.062 ThaliTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 23:52:01.077 ThaliTest[2457:4492691] jxcore: connect 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:52:01.077 ThaliTest[2457:4492691] client: already connect(ing/ed) to 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:11
2016-03-29 23:52:01.077 Tha,liTest[2457:4492691] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,DEBUG testThaliMobileNative: Got recoverable client error Already connect(ing/ed)
,2016-03-29 23:52:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:52:08.377 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:52:08.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:52:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:52:28.377 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:52:28.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:52:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:52:48.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:52:48.375 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:52:54.706 ThaliTest[2457:4494483] server session: not connected E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:52:55.201 ThaliTest[2457:4492520] client: socket closed
2016-03-29 23:52:55.201 ThaliTest[2457:4492520] client relay: socket disconnected
2016-03-29 23:52:55.202 ThaliTest[2457:4492520] client relay: 0x1a076140 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-03-29 23:52:55.202 ThaliTest[2457:4492520] client session: socket closed: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
20,16-03-29 23:52:55.202 ThaliTest[2457:4492520] client session: onLinkFailure: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F
2016-03-29 23:52:55.202 ThaliTest[2457:4492520] client session: disconnect
2016-03-29 23:52:55.202 ThaliTest[2457:4492520] client session: s,tateChange:2->0 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
DEBUG testThaliMobileNative: Got recoverable client error Error: We timed out
DEBUG testThaliMobileNative: Got to close without error or end!
not ok 200 At least one should fire before we hit close
  ---
    operator: ok
    expected: true
,    actual:   false
  ...
,2016-03-29 23:53:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:53:08.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:53:08.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:53:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:53:28.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:53:28.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:53:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:53:48.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:53:48.377 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:54:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:54:08.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:54:08.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:54:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:54:28.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:54:28.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:54:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:54:48.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:54:48.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:55:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:55:08.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:55:08.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:55:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:55:28.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:55:28.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:55:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:55:48.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:55:48.377 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:56:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:56:08.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:56:08.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:56:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:56:28.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:56:28.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:56:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:56:48.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:56:48.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:57:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:57:08.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:57:08.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:57:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:57:28.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:57:28.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:57:48.363 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:57:48.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:57:48.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:58:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:58:08.375 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:58:08.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:58:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:58:28.378 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:58:28.378 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:58:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:58:48.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:58:48.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:59:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:59:08.377 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-29 23:59:08.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:59:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:59:33.078 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-29 23:59:33.079 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-29 23:59:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-29 23:59:48.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-29 23:59:48.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:00:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:00:08.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
2016-03-30 00:00:08.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:00:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:00:28.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:00:28.376 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:00:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:00:48.377 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:00:48.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:01:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:01:08.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:01:08.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:01:28.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:01:28.377 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:01:28.379 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:01:48.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:01:48.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
2016-03-30 00:01:48.378 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13
,2016-03-30 00:02:08.364 ThaliTest[2457:4492520] multipeer manager: restart client
,2016-03-30 00:02:08.376 ThaliTest[2457:4492520] client: found existing peer: E4612A32-7792-490E-A387-1EC57335E3B6:13
,2016-03-30 00:02:08.379 ThaliTest[2457:4492520] client: found existing peer: 7E69AB12-44FB-4D43-AD41-F3672D83BC4F:13

```
