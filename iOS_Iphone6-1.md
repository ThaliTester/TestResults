#### Test 6539483973f7970_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/95642BF4-CE06-4BFC-98AF-A0A9DDCECE44/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/95642BF4-CE06-4BFC-98AF-A0A9DDCECE44/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app' (armv7).
,(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51004"
,(lldb)     command script import "/tmp/95642BF4-CE06-4BFC-98AF-A0A9DDCECE44/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-04-06 03:09:48.612 ThaliTest[2836:5520401] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/23207496-6C73-4552-8F29-DB4E9C6F242E/Library/Cookies/Cookies.binarycookies
,2016-04-06 03:09:48.846 ThaliTest[2836:5520401] Apache Cordova native platform version 4.1.0 is starting.
2016-04-06 03:09:48.847 ThaliTest[2836:5520401] Multi-tasking -> Device: YES, App: YES
,2016-04-06 03:09:48.861 ThaliTest[2836:5520401] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-06 03:09:49.639 ThaliTest[2836:5520401] Using UIWebView
2016-04-06 03:09:49.641 ThaliTest[2836:5520401] [CDVTimer][handleopenurl] 0.123978ms
,2016-04-06 03:09:49.645 ThaliTest[2836:5520401] [CDVTimer][intentandnavigationfilter] 3.314018ms
2016-04-06 03:09:49.645 ThaliTest[2836:5520401] [CDVTimer][gesturehandler] 0.131011ms
2016-04-06 03:09:49.645 ThaliTest[2836:5520401] [CDVTimer][TotalPluginStartup] 4.061997ms
,2016-04-06 03:09:52.749 ThaliTest[2836:5520401] Resetting plugins due to page load.
,2016-04-06 03:09:54.007 ThaliTest[2836:5520401] Finished load of: file:///var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/index.html
,2016-04-06 03:09:54.160 ThaliTest[2836:5520401] JXcore Cordova plugin initializing
,2016-04-06 03:09:54.162 ThaliTest[2836:5520594] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-06 03:10:01.593 ThaliTest[2836:5520594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-06 03:10:01.593 ThaliTest[2836:5520594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-06 03:10:01.594 ThaliTest[2836:5,520594] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-06 03:10:01.597 ThaliTest[2836:5520594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F5E27D39-5D54-4CDD-88E6-737C2065EF43/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57648
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57650
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
,DEBUG createNativeListener: listening 57653
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
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57657
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57662
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 57666
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
DEBUG createNativeListener: listening 57670
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
DEBUG createNativeListener: listening 57674
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 57678
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
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 57730
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: listening 57734
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
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
ok 69 firstPromise - in catch
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
# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"23004744-777a-4286-80e8-7c39ced52031","data":"custom data"},{"uuid":"b9648362-bd7c-4ccf-8c9e-e657f2368bf5","data":"custom data"},{"uuid":"1e708892-c95f-4713-9eb4-ebedb0ff7757","data":"custom data"},{"uuid":"c99173ba-aafb-407b-a44f-72a198cb56d8","data":"custom data"}]
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
DEBUG createNativeListener: listening 57744
,2016-04-06 03:13:22.059 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.061 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 e,rror should be null
2016-04-06 03:13:22.062 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.063, ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
,# teardown
,2016-04-06 03:13:22.246 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:22.247 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:22.247 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:22.247 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.248 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57746
,2016-04-06 03:13:22.446 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
,2016-04-06 03:13:22.446 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:13:22.447 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
,2016-04-06 03:13:22.453 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:13:22.454 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-06 03:13:22.756 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:22.756 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:22.756 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:22.757 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
2016-04-06 03:13:22.757 ThaliTest[2836:5520594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.757 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57748
2016-04-06 03:13:23.232 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:23.232 ThaliTest[2836:5520594] server: starting BA,9EDD0A-C19B-44DC-B46A-4F5B1C971E76:1
2016-04-06 03:13:23.233 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
2016-04-06 03:13:23.233 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:1
2016-04-06 03:13:23.233 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
ok 103 error should be null
ok 104 error should be null
2016-04-06 03:13:23.239 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:23.239 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
,2016-04-06 03:13:23.239 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:13:23.239 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:2
2016-04-06 03:13:23.240 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
2016-04-06 03:13:23.240 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:2
2016-04-06 03:13:23.240 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-06 03:13:23.398 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:23.398 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:23.398 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:13:23.398 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:23.398 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:23.399 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57753
2016-04-06 03:13:42.405 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:42.405 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:42.405 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
2016-04-06 03:13:42.406 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:42.406 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:42.407 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
,ok 112 error should be null
# teardown
,2016-04-06 03:13:46.766 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:46.767 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:46.767 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:46.767 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:46.767 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57755
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-06 03:13:58.985 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:58.985 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:58.985 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:58.985 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:58.986 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57757
2016-04-06 03:13:59.184 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
2016-04-06 03:13:59.184 ThaliTest[2836:5520594] multipeer manager: sta,rt client restart timer: 0x14de34a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:13:59.185 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
,2016-04-06 03:13:59.190 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:59.190 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:3
2016-04-06 03:13:59.191 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:3
2016-04-06 03:13:59.191 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-06 03:13:59.464 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:59.464 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:13:59.465 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:59.465 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
2016-04-06 03:13:59.465 ThaliTest[2836:5520594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:59.465 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
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
ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
,ok 137 error should be null
# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-06 03:14:46.098 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
2016-04-06 03:14:46.098 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.099 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-06 03:14:46.100 ThaliTes,t[2836:5520594] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:46.100 ThaliTest[2836:5520594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-04-06 03:14:46.100 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-06 03:14:46.341 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:46.342 ThaliTest[2836:55205,94] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:46.343 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:46.343 ThaliTest[2836:55205,94] THEMultipeerManager stopping peer
2016-04-06 03:14:46.343 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-06 03:14:46.510 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
2016-04-06 03:14:46.510 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.511 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-06 03:14:46.512 ThaliTes,t[2836:5520594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.512 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-06 03:14:46.870 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:46.870 ThaliTest[2836:5520594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:46.871 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:46.871 ThaliTest[2836:5520,594] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:46.871 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:14:46.871 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-06 03:14:47.051 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.052 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-06 03:14:47.052 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.053 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-06 03:14:58.997 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:58.997 ThaliTest[2836:55205,94] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:58.998 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:58.998 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:14:58.998 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-06 03:15:33.647 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:33.647 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:4
2016-04-06 03:15:33.647 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
2016-04-06 03:15:33.648 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:4
2016-04-06 03:15:33.648 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:33.648 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:33.649 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
,2016-04-06 03:15:33.649 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:15:33.652 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-06 03:15:33.894 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:15:33.894 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:15:33.895 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:33.895 ThaliTest[2836:55205,94] THEMultipeerManager stopping peer
2016-04-06 03:15:33.895 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-06 03:15:34.611 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:34.611 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:5
2016-04-06 03:15:34.611 ThaliTest[2836:5520594] multipeer m,anager: start client restart timer: 0x14de34a0
2016-04-06 03:15:34.612 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:5
,2016-04-06 03:15:34.614 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:34.615 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListenin,g
2016-04-06 03:15:34.615 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:15:34.615 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:15:34.615 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
,2016-04-06 03:15:34.619 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
2016-04-06 03:15:34.619 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
2016-04-06 03:15:34.619 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-06 03:15:39.788 ThaliTest[2836:5520401] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
,2016-04-06 03:15:41.699 ThaliTest[2836:5520401] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:6
,2016-04-06 03:15:42.076 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-06 03:15:42.077 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:15:42.078 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:42.078 ThaliTest[2836:552059,4] THEMultipeerManager stopping peer
2016-04-06 03:15:42.078 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:15:42.078 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-06 03:16:38.035 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.035 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:16:38.035 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:16:38.035 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.035 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:16,:38.036 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-06 03:16:38.125 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:16:38.126 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:38.126 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.126 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:16:38.126 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-06 03:16:38.373 ThaliTest[2836:5520594] jxcore: connect foo
2016-04-06 03:16:38.374 ThaliTest[2836:5520594] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-06 03:16:38.484 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:16:38.485 ThaliTest[2836:55205,94] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:38.485 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.486 ThaliTest[2836:55205,94] THEMultipeerManager stopping peer
2016-04-06 03:16:38.486 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-06 03:16:38.653 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:16:38.653 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:38.654 ThaliTest[2836:5520594] multipeer m,anager: start client restart timer: 0x14de34a0
2016-04-06 03:16:38.654 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
2016-04-06 03:16:38.654 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-06 03:16:38.655 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-06 03:16:38.655 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:40.697 ThaliTest[2836:5520401] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:6
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
2016-04-06 03:16:40.701 ThaliTest[2836:5520401] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
# teardown
2016-04-06 03:16:40.702 ThaliTest[2836:5520401] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:46.321 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:16:46.322 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:16:46.323 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:46.323 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:16:46.323 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:16:46.323 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-06 03:16:47.011 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:16:47.011 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:16:47.012 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
2016-04-06 03:16:47.012 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:16:47.012 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:16:47.013 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-06 03:16:47.013 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:47.956 ThaliTest[2836:5520401] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:47.957 ThaliTest[2836:5520401] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:16:47.957 ThaliTest[2836:5520401] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7","pleaseConnect":0}]
2016-04-06 03:16:47.957 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:47.958 ThaliTest[2836:5520594] client session: connect
,2016-04-06 03:16:47.958 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:7","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"8C5B19F5-9879-44C8-A20C-4970704F4B6A:7","pleaseConnect":0}]
,2016-04-06 03:16:48.274 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:16:48.274 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:16:49.255 ThaliTest[2836:5521441] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:49.256 ThaliTest[2836:5521441] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:49.256 ThaliTest[2836:5521441] client session: disconnect
2016-04-06 03:16:49.256 ThaliTest[2836:5521441] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:49.257 ThaliTest[2836:5521441] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:49.257 ThaliTest[2836:5521441] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:16:51.743 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:16:51.743 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:16:51.743 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:16:52.260 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:52.260 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:16:52.260 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:52.343 ThaliTest[2836:5521469] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:52.343 ThaliTest[2836:5521469] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:52.343 ThaliTest[2836:5521469] client session: disconnect
,2016-04-06 03:16:52.343 ThaliTest[2836:5521469] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:52.344 ThaliTest[2836:5521469] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:52.344 ThaliTest[2836:5521469] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:16:54.952 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:16:54.952 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:16:54.952 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:16:55.348 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:55.348 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:16:55.348 ThaliTest[2836:5520594] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:55.484 ThaliTest[2836:5521439] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:55.484 ThaliTest[2836:5521439] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:55.484 ThaliTest[2836:5521439] client session: disconnect
2016-04-06 03:16:55.484 ThaliTest[2836:5521439] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:55.485 ThaliTest[2836:5521439] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:55.485 ThaliTest[2836:5521439] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:16:58.100 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:16:58.101 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:16:58.101 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:16:58.495 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:58.496 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:16:58.496 ThaliTest[2836:5520594] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:16:58.608 ThaliTest[2836:5521439] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:58.608 ThaliTest[2836:5521439] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:58.6,08 ThaliTest[2836:5521439] client session: disconnect
2016-04-06 03:16:58.608 ThaliTest[2836:5521439] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:58.608 ThaliTest[2836:5521439] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:16:58.608 ThaliTest[2836:5521439] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-04-06 03:17:01.248 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:17:01.248 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:17:01.249 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:17:01.611 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:01.611 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:17:01.611 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:17:01.763 ThaliTest[2836:5521439] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:01.764 ThaliTest[2836:5521439] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:17:01.764 ThaliTest[2836:5521439] client session: disconnect
2016-04-06 03:17:01.764 ThaliTest[2836:5521439] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:17:01.765 ThaliTest[2836:5521439] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:01.765 ThaliTest[2836:5521439] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:17:04.348 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:17:04.349 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:17:04.349 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:17:04.768 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:04.769 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:17:04.769 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
,2016-04-06 03:17:04.868 ThaliTest[2836:5521440] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:04.868 ThaliTest[2836:5521440] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:04.868 ThaliTest[2836:5521440] client session: disconnect
,2016-04-06 03:17:04.869 ThaliTest[2836:5521440] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:04.869 ThaliTest[2836:5521440] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:04.870 ThaliTest[2836:5521440] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:17:07.013 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:17:07.028 ThaliTest[2836:5520401] client: found updated peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:07.029 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:17:07.029 ThaliTest[2836:5520401] client: found updated peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"8C5B19F5-9879-44C8-A20C-4970704F4B6A:8","pleaseConnect":0}]
,2016-04-06 03:17:07.540 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:17:07.540 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:17:07.540 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:17:07.878 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:07.879 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:17:07.879 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:08.058 ThaliTest[2836:5521441] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:08.060 ThaliTest[2836:5521441] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:08.0,60 ThaliTest[2836:5521441] client session: disconnect
2016-04-06 03:17:08.060 ThaliTest[2836:5521441] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:08.060 ThaliTest[2836:5521441] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:08.060 ThaliTest[2836:5521441] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:17:10.680 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:17:10.680 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:17:10.680 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:17:11.069 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:11.069 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:17:11.069 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:11.205 ThaliTest[2836:5521441] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:11.205 ThaliTest[2836:5521441] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:11.2,05 ThaliTest[2836:5521441] client session: disconnect
2016-04-06 03:17:11.206 ThaliTest[2836:5521441] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:11.206 ThaliTest[2836:5521441] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:11.206 ThaliTest[2836:5521441] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:17:13.894 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:17:13.894 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:17:13.894 ThaliTest[2836:5520401] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:17:14.216 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:14.216 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:17:14.216 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:14.352 ThaliTest[2836:5521441] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:14.352 ThaliTest[2836:5521441] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:14.3,53 ThaliTest[2836:5521441] client session: disconnect
2016-04-06 03:17:14.353 ThaliTest[2836:5521441] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:14.353 ThaliTest[2836:5521441] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:14.353 ThaliTest[2836:5521441] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:17:17.037 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:17:17.037 ThaliTest[2836:5520401] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:17:17.037 ThaliTest[2836:5520401], server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7)
,2016-04-06 03:17:17.354 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:17:17.354 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:17:17.354 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:17.563 ThaliTest[2836:5521469] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:17.564 ThaliTest[2836:5521469] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:17.565 ThaliTest[2836:5521469] client session: disconnect
2016-04-06 03:17:17.565 ThaliTest[2836:5521469] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:17.565 ThaliTest[2836:5521469] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:17:17.565 ThaliTest[2836:5521469] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
  ...
,# teardown
,2016-04-06 03:17:27.012 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:17:27.024 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:27.024 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:17:27.024 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:17:47.013 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:17:47.027 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:17:47.027 ThaliTest[2836:5520401] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:17:47.028 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:8","pleaseConnect":0}]
,2016-04-06 03:18:07.013 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:18:07.029 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:07.030 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:07.030 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:18:27.013 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:18:27.028 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:27.028 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:27.032 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:18:47.013 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:18:47.024 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:47.024 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:47.024 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:18:56.173 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:18:56.173 ThaliTest[2836:5520594] jxcore: stopListeningForAdvertisements: success
ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:18:56.174 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening
2016-04-06 03:18:56.174 ThaliTest[2836:5520594] THEMultipeerManager stopping peer
2016-04-06 03:18:56.175 ThaliTest[2836:5520594] multipeer manager: stop client timer
2016-04-06 03:18:56.175 ThaliTest[2836:5520594] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-06 03:18:56.417 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:18:56.417 ThaliTest[2836:5520594] server: starting BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:18:56.417 ThaliTest[2836:5520594] multipeer manager: start client restart timer: 0x14de34a0
2016-04-06 03:18:56.417 ThaliTest[2836:5520594] THEMultipeerManager initialized peer BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:18:56.417 ThaliTest[2836:5520594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:18:56.418 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-06 03:18:56.419 ThaliTest[2836:5520594] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-06 03:18:57.289 ThaliTest[2836:5520401] client: found new peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:57.289 ThaliTest[2836:5520401] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:57.289 ThaliTes,t[2836:5520401] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:57.290 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:57.290 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:18:57.290 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:18:58.578 ThaliTest[2836:5521848] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:58.579 ThaliTest[2836:5521848] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:18:58.579 ThaliTest[2836:5521848] client session: disconnect
2016-04-06 03:18:58.579 ThaliTest[2836:5521848] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:18:58.579 ThaliTest[2836:5521848] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:18:58.580 ThaliTest[2836:5521848] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:18:59.005 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:18:59.005 ThaliTest[2836:5520401] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8)
,2016-04-06 03:19:01.587 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:01.588 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:01.588 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:02.198 ThaliTest[2836:5521863] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:02.198 ThaliTest[2836:5521863] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:02.198 ThaliTest[2836:5521863] client session: disconnect
2016-04-06 03:19:02.198 ThaliTest[2836:5521863] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:02.199 ThaliTest[2836:5521863] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:02.199 ThaliTest[2836:5521863] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:19:05.203 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:05.203 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:05.203 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:06.004 ThaliTest[2836:5521863] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:06.004 ThaliTest[2836:5521863] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:06.0,04 ThaliTest[2836:5521863] client session: disconnect
2016-04-06 03:19:06.004 ThaliTest[2836:5521863] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:06.004 ThaliTest[2836:5521863] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:06.005 ThaliTest[2836:5521863] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-04-06 03:19:09.012 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:09.012 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:09.012 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:09.669 ThaliTest[2836:5521863] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:09.669 ThaliTest[2836:5521863] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:09.669 ThaliTest[2836:5521863] client session: disconnect
,2016-04-06 03:19:09.669 ThaliTest[2836:5521863] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:09.670 ThaliTest[2836:5521863] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:09.670 ThaliTest[2836:5521863] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:19:10.590 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:19:10.590 ThaliTest[2836:5520401] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:19:10.590 ThaliTest[2836:5520401] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8)
,2016-04-06 03:19:12.678 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:12.678 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:12.678 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:12.777 ThaliTest[2836:5521874] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:12.777 ThaliTest[2836:5521874] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:12.777 ThaliTest[2836:5521874] client session: disconnect
2016-04-06 03:19:12.777 ThaliTest[2836:5521874] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:12.777 ThaliTest[2836:5521874] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:12.777 ThaliTest[2836:5521874] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 5
,2016-04-06 03:19:15.788 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:15.788 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:15.788 ThaliTest[2836:5520594] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
,2016-04-06 03:19:15.913 ThaliTest[2836:5521952] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:15.914 ThaliTest[2836:5521952] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:15.914 ThaliTest[2836:5521952] client session: disconnect
2016-04-06 03:19:15.914 ThaliTest[2836:5521952] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:15.914 ThaliTest[2836:5521952] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:15.914 ThaliTest[2836:5521952] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:19:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:19:16.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:16.429 ThaliTest[2836:5520401] client: found updated peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:16.429 ThaliTest[2836:5520401] client: found updated peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:19:18.916 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:18.916 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:18.916 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:19.219 ThaliTest[2836:5521952] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:19.219 ThaliTest[2836:5521952] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:19.219 ThaliTest[2836:5521952] client session: disconnect
,2016-04-06 03:19:19.220 ThaliTest[2836:5521952] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:19.220 ThaliTest[2836:5521952] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:19.220 ThaliTest[2836:5521952] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:19:22.230 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:22.230 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:22.231 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:22.301 ThaliTest[2836:5521951] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:22.301 ThaliTest[2836:5521951] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
,2016-04-06 03:19:22.301 ThaliTest[2836:5521951] client session: disconnect
2016-04-06 03:19:22.301 ThaliTest[2836:5521951] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:22.302 ThaliTest[2836:5521951] client session: fireConnectCallback: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:22.303 ThaliTest[2836:5521951] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:19:23.488 ThaliTest[2836:5520401] multipeer session: reset timer
2016-04-06 03:19:23.488 ThaliTest[2836:5520401] server: disconnecting to refresh session (8C5B19F5-9879-44C8-A20C-4970704F4B6A)
2016-04-06 03:19:23.489 ThaliTest[2836:5520401] server: rejecting invitation from 8C5B19F5-9879-44C8-A20C-4970704F4B6A due to previous generation (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9 != BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8)
,2016-04-06 03:19:25.307 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:25.307 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:25.307 ThaliTest[2836:5520594] client session: stateChange:0->1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:25.397 ThaliTest[2836:5521951] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:25.398 ThaliTest[2836:5521951] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:25.399 ThaliTest[2836:5521951] client session: disconnect
2016-04-06 03:19:25.399 ThaliTest[2836:5521951] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:25.399 ThaliTest[2836:5521951] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:25.399 ThaliTest[2836:5521951] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:19:28.409 ThaliTest[2836:5520594] jxcore: connect 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:19:28.409 ThaliTest[2836:5520594] client session: connect
2016-04-06 03:19:28.409 ThaliTest[2836:5520594] client session: stateChange:0->,1 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:19:28.999 ThaliTest[2836:5521950] client session: not connected 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:28.999 ThaliTest[2836:5521950] client session: onLinkFailure: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:28.9,99 ThaliTest[2836:5521950] client session: disconnect
2016-04-06 03:19:28.999 ThaliTest[2836:5521950] client session: stateChange:1->0 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:28.999 ThaliTest[2836:5521950] client session: fireConnectCallb,ack: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D
2016-04-06 03:19:29.000 ThaliTest[2836:5521950] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,2016-04-06 03:19:36.417 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:19:36.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:19:36.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:36.429 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:19:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:19:56.430 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:56.430 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:19:56.430 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:20:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:20:16.434 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:16.434 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:20:16.435 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:20:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:20:36.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:36.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:36.430 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:20:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:20:56.430 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:20:56.431 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:56.431 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:21:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:21:16.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:21:16.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:21:16.430 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:21:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:21:36.431 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:21:36.431 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:21:36.431 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:21:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:22:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:22:16.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:16.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:22:16.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:22:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:22:36.431 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:22:36.431 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:36.431 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:22:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:22:56.429 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:56.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:22:56.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:23:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:23:16.431 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:23:16.431 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:23:16.431 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:23:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:23:36.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:36.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:23:36.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:23:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:23:56.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:23:56.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:56.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:24:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:24:16.429 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:16.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:24:16.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:24:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:24:36.428 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:24:36.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:36.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:24:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:24:56.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:24:56.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:56.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:25:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:25:16.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:16.429 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:25:16.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:25:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:25:36.430 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:25:36.430 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:25:36.432 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:25:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:25:56.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:25:56.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:25:56.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:26:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:26:16.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:26:16.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:26:16.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:26:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:26:36.430 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:26:36.431 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:26:36.431 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:26:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:26:56.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:26:56.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:26:56.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:27:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:27:16.430 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:27:16.430 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:27:16.431 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:27:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:27:36.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:36.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:27:36.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:27:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:27:56.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:27:56.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:56.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:28:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:28:16.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:16.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:28:16.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:28:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:28:36.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:36.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:28:36.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:28:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:28:56.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:56.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:28:56.428 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:29:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:29:16.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:29:16.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:29:16.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
,2016-04-06 03:29:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:29:36.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:29:36.428 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:29:36.429 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:29:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:29:56.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:29:56.429 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:29:56.429 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:30:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:30:16.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:30:16.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:16.427 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:30:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:30:36.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:36.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:30:36.428 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:30:56.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:30:56.427 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:56.427 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:30:56.427 ThaliTest[2836:5520401] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:30:56.428 ThaliTest[2836:5520594] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:30:56.428 ThaliTest[2836:5520594] client: server will connect
2016-04-06 03:30:56.428 ThaliTest[2836:5520594] client session: reverseConnect
2016-04-06 03:30:56.429 ThaliTest[2836:5520594] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:30:57.446 ThaliTest[2836:5521950] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:30:57.446 ThaliTest[2836:5521950] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:30:57.448 ThaliTest[2836:5521950] client session: disconnect
2016-04-06 03:30:57.448 ThaliTest[2836:5521950] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:30:57.448 ThaliTest[2836:5521950] client session: no connect callback (server initiated)
,2016-04-06 03:31:06.429 ThaliTest[2836:5520401] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:31:09.436 ThaliTest[2836:5520594] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:09.436 ThaliTest[2836:5520594] client: server will connect
2016-04-06 03:31:09.436 ThaliTest[2836:5520594] client session: reverseConn,ect
2016-04-06 03:31:09.436 ThaliTest[2836:5520594] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:09.556 ThaliTest[2836:5524251] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:09.557 ThaliTest[2836:5524251] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:31:09.557 ThaliTest[2836:5524251] client session: disconnect
2016-04-06 03:31:09.557 ThaliTest[2836:5524251] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:09.558 ThaliTest[2836:5524251] client session: no connect callback (server initiated)
,2016-04-06 03:31:16.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:31:16.428 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:31:16.428 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:31:16.429 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:19.437 ThaliTest[2836:5520401] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:31:22.442 ThaliTest[2836:5520594] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:22.443 ThaliTest[2836:5520594] client: server will connect
2016-04-06 03:31:22.443 ThaliTest[2836:5520594] client session: reverseConnect
2016-04-06 03:31:22.443 ThaliTest[2836:5520594] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:22.606 ThaliTest[2836:5524251] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:22.606 ThaliTest[2836:5524251] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
,2016-04-06 03:31:22.606 ThaliTest[2836:5524251] client session: disconnect
2016-04-06 03:31:22.607 ThaliTest[2836:5524251] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:22.607 ThaliTest[2836:5524251] client session: no connect callback (server initiated)
,2016-04-06 03:31:32.444 ThaliTest[2836:5520401] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:31:35.449 ThaliTest[2836:5520594] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:35.449 ThaliTest[2836:5520594] client: server will connect
2016-04-06 03:31:35.449 ThaliTest[2836:5520594] client session: reverseConnect
2016-04-06 03:31:35.449 ThaliTest[2836:5520594] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:35.646 ThaliTest[2836:5524333] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:35.646 ThaliTest[2836:5524333] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:31:35.646 ThaliTest[2836:5524333] client session: disconnect
2016-04-06 03:31:35.646 ThaliTest[2836:5524333] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:35.647 ThaliTest[2836:5524333] client session: no connect callback (server initiated)
,2016-04-06 03:31:36.418 ThaliTest[2836:5520401] multipeer manager: restart client
,2016-04-06 03:31:36.430 ThaliTest[2836:5520401] client: found existing peer: 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:31:36.431 ThaliTest[2836:5520401] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:36.43,1 ThaliTest[2836:5520401] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:31:45.450 ThaliTest[2836:5520401] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:31:48.453 ThaliTest[2836:5520594] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:48.454 ThaliTest[2836:5520594] client: server will connect
,2016-04-06 03:31:48.454 ThaliTest[2836:5520594] client session: reverseConnect
2016-04-06 03:31:48.454 ThaliTest[2836:5520594] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:48.813 ThaliTest[2836:5524333] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:48.814 ThaliTest[2836:5524333] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
,2016-04-06 03:31:48.815 ThaliTest[2836:5524333] client session: disconnect
,2016-04-06 03:31:48.815 ThaliTest[2836:5524333] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:31:48.815 ThaliTest[2836:5524333] client session: no connect callback (server initiated)

```
