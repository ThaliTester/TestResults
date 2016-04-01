#### Test 64613803d18c8d9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/59A09F03-1D78-4F92-9AFF-9B6ADA8756B1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/59A09F03-1D78-4F92-9AFF-9B6ADA8756B1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50048"
,(lldb)     command script import "/tmp/59A09F03-1D78-4F92-9AFF-9B6ADA8756B1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 07:17:20.165 ThaliTest[2642:4831733] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1184EFC-4F40-4C24-9DAD-902F24190EFB/Library/Cookies/Cookies.binarycookies
,2016-04-01 07:17:20.417 ThaliTest[2642:4831733] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 07:17:20.418 ThaliTest[2642:4831733] Multi-tasking -> Device: YES, App: YES
,2016-04-01 07:17:20.435 ThaliTest[2642:4831733] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 07:17:21.237 ThaliTest[2642:4831733] Using UIWebView
,2016-04-01 07:17:21.240 ThaliTest[2642:4831733] [CDVTimer][handleopenurl] 0.355005ms
,2016-04-01 07:17:21.243 ThaliTest[2642:4831733] [CDVTimer][intentandnavigationfilter] 2.812982ms
2016-04-01 07:17:21.243 ThaliTest[2642:4831733] [CDVTimer][gesturehandler] 0.132978ms
2016-04-01 07:17:21.243 ThaliTest[2642:4831733] [CDVTimer][TotalPluginStartup] 4.007041ms
,2016-04-01 07:17:24.455 ThaliTest[2642:4831733] Resetting plugins due to page load.
,2016-04-01 07:17:25.954 ThaliTest[2642:4831733] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/index.html
,2016-04-01 07:17:26.144 ThaliTest[2642:4831733] JXcore Cordova plugin initializing
2016-04-01 07:17:26.146 ThaliTest[2642:4831882] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 07:17:34.486 ThaliTest[2642:4831882] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 07:17:34.486 ThaliTest[2642:4831882] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 07:17:34.486 ThaliTest[2642:4,831882] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 07:17:34.488 ThaliTest[2642:4831882] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3C846322-F39B-455D-903A-5EA532937CF9/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57643
,ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57645
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57648
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57652
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57657
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
DEBUG createNativeListener: listening 57661
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
DEBUG createNativeListener: listening 57665
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
DEBUG createNativeListener: listening 57669
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57673
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming ,has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incomi,ng socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57725
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
DEBUG createNativeListener: listening 57729
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
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
,ok 55 thirdPromise result
ok 56 thirdPromise testValue
# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
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
# teardown
,# setup
,# 21. another
,ok 75 sane
# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"fb907fa7-6bbb-4685-a83b-630e712f1cec","data":"custom data"},{"uuid":"2116515a-89f8-4ac6-81c4-f1910b261345","data":"custom data"},{"uuid":"0aa21398-7b4c-4999-b9cc-207fff665ddf","data":"custom data"},{"uuid":"096b47f0-b3ca-42e2-86de-efb223a755a4",",data":"custom data"}]
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
,DEBUG createNativeListener: listening 57739
2016-04-01 07:20:43.421 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false},
2016-04-01 07:20:43.422 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-01 07:20:43.424 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:43.424 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# teardown
,2016-04-01 07:20:43.556 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:43.556 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:20:43.556 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:20:43.556 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:43.557 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57741
2016-04-01 07:20:43.931 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
,2016-04-01 07:20:43.933 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:20:43.934 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 07:20:43.945 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:20:43.946 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-01 07:20:44.274 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:44.274 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:20:44.274 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:20:44.274 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
2016-04-01 07:20:44.274 ThaliTest[2642:4831882] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:44.275 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57743
,2016-04-01 07:20:44.822 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:44.822 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:1
2016-04-01 07:20:44.823 ThaliTest[2642:4831882] multipeer m,anager: start client restart timer: 0x15d76090
2016-04-01 07:20:44.823 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:1
2016-04-01 07:20:44.823 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 07:20:44.835 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:44.836 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:20:44.836, ThaliTest[2642:4831882] multipeer manager: stop client timer
2016-04-01 07:20:44.836 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:2
2016-04-01 07:20:44.836 ThaliTest[2642:4831882] multipeer manager: start client restart ,timer: 0x15d76090
2016-04-01 07:20:44.837 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:2
2016-04-01 07:20:44.837 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
# teardown
,2016-04-01 07:20:44.944 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:44.945 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:20:44.945 ThaliTest[2642:4831882] multipeer manager: stop client timer
20,16-04-01 07:20:44.945 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:20:44.946 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:44.946 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57748
2016-04-01 07:20:50.710 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:50.710 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:20:50.711 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
,2016-04-01 07:20:50.713 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:50.714 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:20:50.714 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-01 07:21:04.709 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:04.709 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:04.709 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:21:04.709 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:04.711 ThaliTest[2642,:4831882] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57750
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-01 07:21:05.276 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:05.276 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:05.276 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:05.276 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:05.277 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57752
2016-04-01 07:21:05.528 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
2016-04-01 07:21:05.528 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:05.529 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
,2016-04-01 07:21:05.570 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:05.570 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:3
2016-04-01 07:21:05.570 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:3
2016-04-01 07:21:05.571 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-01 07:21:05.974 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:05.974 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:05.974 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 07:21:05.974 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:05.974 ThaliTest[2642:4831882] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:05.975 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
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
,ok 135 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 07:21:41.018 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
2016-04-01 07:21:41.018 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:41.021 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAd,vertisements without error
2016-04-01 07:21:41.021 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:41.022 ThaliTest[2642:4831882] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingSt,ateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:41.022 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 07:21:41.313 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:41.314 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:41.315 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:41.315 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:41.315 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: suc,cess
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 07:21:41.966 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
2016-04-01 07:21:41.966 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:41.967 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 07:21:41.967 ThaliTes,t[2642:4831882] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:41.968 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 07:21:42.968 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:42.968 ThaliTest[2642:4831882] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:42.969 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:42.969 ThaliTest[2642:4831,882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:42.969 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:42.970 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 07:21:43.968 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:43.969 ThaliTest[2642:48318,82] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-01 07:21:43.970 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:43.970 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 07:21:44.098 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:44.099 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:44.100 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.100 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:44.100 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 07:21:44.463 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:44.463 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:4
2016-04-01 07:21:44.463 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
2016-04-01 07:21:44.463 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:4
2016-04-01 07:21:44.464 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:44.464 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.464 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
,2016-04-01 07:21:44.465 ThaliTest[2642:4831882] multipeer manager: stop client timer
,2016-04-01 07:21:44.474 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 07:21:44.593 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:44.594 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:44.595 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:44.595 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:44.595 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 07:21:44.970 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:44.971 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:5
2016-04-01 07:21:44.971 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
2016-04-01 07:21:44.971 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:5
2016-04-01 07:21:44.971 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:44.972 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:44.972 ThaliTest[2642:4831882] THEMultipeerManager stopping pee,r
2016-04-01 07:21:44.973 ThaliTest[2642:4831882] multipeer manager: stop client timer
2016-04-01 07:21:44.973 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:6
2016-04-01 07:21:44.973 ThaliTest[2642:4831882] multipeer mana,ger: start client restart timer: 0x15d76090
2016-04-01 07:21:44.976 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:6
2016-04-01 07:21:44.976 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-01 07:21:45.093 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:21:45.094 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:45.096 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:45.097 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
,2016-04-01 07:21:45.100 ThaliTest[2642:4831882] multipeer manager: stop client timer
,2016-04-01 07:21:45.100 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 07:21:45.498 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.498 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:45.498 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 07:21:45.499 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.499 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:21:45.499 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 07:21:59.750 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:21:59.750 ThaliTest[2642:48318,82] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:21:59.751 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:59.751 ThaliTest[2642:48318,82] THEMultipeerManager stopping peer
2016-04-01 07:21:59.751 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 07:22:19.231 ThaliTest[2642:4831882] jxcore: connect foo
2016-04-01 07:22:19.232 ThaliTest[2642:4831882] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvert,isements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-01 07:22:19.972 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:22:19.973 ThaliTest[2642:48318,82] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:19.973 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:19.973 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:22:19.973 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 07:22:20.310 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:20.310 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:20.311 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
2016-04-01 07:22:20.311 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:20.311 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-01 07:22:20.312 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:22:20.312 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:21.265 ThaliTest[2642:4831733] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a strin,g
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 07:22:21.464 ThaliTest[2642:4831733] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,2016-04-01 07:22:21.468 ThaliTest[2642:4831733] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
,2016-04-01 07:22:23.355 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 07:22:23.356 ThaliTest[2642:483188,2] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 07:22:23.356 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:22:23.357 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:22:23.357 ThaliTest[2642:4831882] multipeer manager: stop client timer
2016-04-01 07:22:23.357 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-01 07:22:24.347 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:24.348 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:22:24.348 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
2016-04-01 07:22:24.348 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:22:24.348 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:22:24.352 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:22:24.353 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:25.244 ThaliTest[2642:4831733] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7","pleaseConnect":0}]
,2016-04-01 07:22:25.247 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:25.247 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:25.247 ThaliTest[2642:4831882] client session: stateChange:0->,1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:25.575 ThaliTest[2642:4831733] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:7","pleaseConnect":0}]
,2016-04-01 07:22:26.690 ThaliTest[2642:4831733] multipeer session: reset timer
2016-04-01 07:22:26.690 ThaliTest[2642:4831733] server: rejecting invitation from 444A455A-C80E-416D-9E03-5D6FFDE7B60A due to previous generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:22:26.753 ThaliTest[2642:4831733] multipeer session: reset timer
,2016-04-01 07:22:26.753 ThaliTest[2642:4831733] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:22:26.948 ThaliTest[2642:4832480] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:26.948 ThaliTest[2642:4832480] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:26.948 ThaliTest[2642:4832480] client session: disconnect
2016-04-01 07:22:26.949 ThaliTest[2642:4832480] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:26.950 ThaliTest[2642:4832480] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:26.950 ThaliTest[2642:4832480] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:22:27.576 ThaliTest[2642:4831733] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DBB8C:7","pleaseConnect":0}]
,2016-04-01 07:22:29.958 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:29.958 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:29.959 ThaliTest[2642:4831882] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:30.273 ThaliTest[2642:4832480] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:30.274 ThaliTest[2642:4832480] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:30.2,74 ThaliTest[2642:4832480] client session: disconnect
2016-04-01 07:22:30.274 ThaliTest[2642:4832480] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:30.274 ThaliTest[2642:4832480] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:30.274 ThaliTest[2642:4832480] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 07:22:33.279 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:33.279 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:33.280 ThaliTest[2642:4831882] client session: stateChange:0->,1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:33.968 ThaliTest[2642:4832480] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:33.969 ThaliTest[2642:4832480] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:33.970 ThaliTest[2642:4832480] client session: disconnect
2016-04-01 07:22:33.970 ThaliTest[2642:4832480] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:33.970 ThaliTest[2642:4832480] client session: fireConnectCallb,ack: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:33.970 ThaliTest[2642:4832480] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 07:22:36.980 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:36.980 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:36.980 ThaliTest[2642:4831882] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:37.168 ThaliTest[2642:4832483] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:37.168 ThaliTest[2642:4832483] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:37.1,68 ThaliTest[2642:4832483] client session: disconnect
2016-04-01 07:22:37.168 ThaliTest[2642:4832483] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:37.168 ThaliTest[2642:4832483] client session: fireConnectCallb,ack: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:37.169 ThaliTest[2642:4832483] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 07:22:38.425 ThaliTest[2642:4831733] multipeer session: reset timer
,2016-04-01 07:22:38.426 ThaliTest[2642:4831733] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:22:38.426 ThaliTest[2642:4831733] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to p,revious generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:22:38.430 ThaliTest[2642:4831733] multipeer session: reset timer
2016-04-01 07:22:38.430 ThaliTest[2642:4831733] server: disconnecting to refresh session (444A455A-C80E-416D-9E03-5D6FFDE7B60A)
2016-04-01 07:22:38.430 ThaliTest[2642:4831733] server: rejecting invitation from 444A455A-C80E-416D-9E03-5D6FFDE7B60A due to previous generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:22:40.174 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:40.175 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:40.175 ThaliTest[2642:4831882] client session: stateChange:0->,1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:40.786 ThaliTest[2642:4832452] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:40.787 ThaliTest[2642:4832452] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:40.7,87 ThaliTest[2642:4832452] client session: disconnect
,2016-04-01 07:22:40.787 ThaliTest[2642:4832452] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:40.789 ThaliTest[2642:4832452] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 0,7:22:40.789 ThaliTest[2642:4832452] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:22:43.801 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:43.801 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:43.802 ThaliTest[2642:4831882] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:44.042 ThaliTest[2642:4832451] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:44.042 ThaliTest[2642:4832451] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:44.0,43 ThaliTest[2642:4832451] client session: disconnect
2016-04-01 07:22:44.043 ThaliTest[2642:4832451] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,2016-04-01 07:22:44.044 ThaliTest[2642:4832451] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:44.044 ThaliTest[2642:4832451] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 07:22:44.349 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:22:44.364 ThaliTest[2642:4831733] client: found updated peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:22:44.365 ThaliTest[2642:4831733] client: found updated peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:22:44.365 ThaliTest[2642:4831733] client: found updated peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"775127D1-BE71-46C7-B433-2FA7873DBB8C:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8","pleaseConnect":0}]
,2016-04-01 07:22:47.046 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:47.046 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:47.046 ThaliTest[2642:4831882] client session: stateChange:0->,1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:47.544 ThaliTest[2642:4832564] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:47.544 ThaliTest[2642:4832564] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:47.544 ThaliTest[2642:4832564] client session: disconnect
2016-04-01 07:22:47.544 ThaliTest[2642:4832564] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:47.545 ThaliTest[2642:4832564] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:47.545 ThaliTest[2642:4832564] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-04-01 07:22:50.558 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:50.558 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:50.558 ThaliTest[2642:4831882] client session: stateChange:0->,1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:51.289 ThaliTest[2642:4832452] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:51.289 ThaliTest[2642:4832452] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:22:51.289 ThaliTest[2642:4832452] client session: disconnect
2016-04-01 07:22:51.290 ThaliTest[2642:4832452] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:51.291 ThaliTest[2642:4832452] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:51.291 ThaliTest[2642:4832452] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 07:22:51.361 ThaliTest[2642:4831733] multipeer session: reset timer
2016-04-01 07:22:51.361 ThaliTest[2642:4831733] server: disconnecting to refresh session (444A455A-C80E-416D-9E03-5D6FFDE7B60A)
2016-04-01 07:22:51.361 ThaliTest[2642:4831733] server: rejecting invitation from 444A455A-C80E-416D-9E03-5D6FFDE7B60A due to previous generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:22:51.797 ThaliTest[2642:4831733] multipeer session: reset timer
2016-04-01 07:22:51.797 ThaliTest[2642:4831733] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:22:51.797 ThaliTest[2642:4831733] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:22:54.298 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:54.299 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:54.299 ThaliTest[2642:4831882] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:54.532 ThaliTest[2642:4832452] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:54.532 ThaliTest[2642:4832452] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:54.5,32 ThaliTest[2642:4832452] client session: disconnect
,2016-04-01 07:22:54.532 ThaliTest[2642:4832452] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:54.534 ThaliTest[2642:4832452] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:54.534 ThaliTest[2642:4832452] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 07:22:57.536 ThaliTest[2642:4831882] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
2016-04-01 07:22:57.536 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:22:57.536 ThaliTest[2642:4831882] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:58.072 ThaliTest[2642:4832556] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:58.072 ThaliTest[2642:4832556] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:58.074 ThaliTest[2642:4832556] client session: disconnect
2016-04-01 07:22:58.074 ThaliTest[2642:4832556] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:22:58.074 ThaliTest[2642:4832556] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:22:58.074 ThaliTest[2642:4832556] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-04-01 07:23:04.349 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:23:04.375 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:23:04.375 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:04.376 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:23:04.435 ThaliTest[2642:4831733] multipeer session: reset timer
,2016-04-01 07:23:04.436 ThaliTest[2642:4831733] server: disconnecting to refresh session (775127D1-BE71-46C7-B433-2FA7873DBB8C)
2016-04-01 07:23:04.436 ThaliTest[2642:4831733] server: rejecting invitation from 775127D1-BE71-46C7-B433-2FA7873DBB8C due to previous generation (A956A86E-53B4-4DBF-B193-1271D200C497:8 != A956A86E-53B4-4DBF-B193-1271D200C497:7)
,2016-04-01 07:23:24.349 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:23:24.366 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:24.366 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:23:24.367 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:23:44.349 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:23:44.364 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:44.365 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:23:44.366 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:04.349 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:24:05.057 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:05.059 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:05.059 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:24:05.278 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:24:05.280 ThaliTest[2642:4831882] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:24:05.281 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening
2016-04-01 07:24:05.281 ThaliTest[2642:4831882] THEMultipeerManager stopping peer
2016-04-01 07:24:05.281 ThaliTest[2642:4831882] multipeer manager: stop client timer
20,16-04-01 07:24:05.282 ThaliTest[2642:4831882] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 07:24:07.502 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:24:07.503 ThaliTest[2642:4831882] server: starting A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:24:07.503 ThaliTest[2642:4831882] multipeer manager: start client restart timer: 0x15d76090
2016-04-01 07:24:07.503 ThaliTest[2642:4831882] THEMultipeerManager initialized peer A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:24:07.503 ThaliTest[2642:4831882] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:24:07.504 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-01 07:24:07.505 ThaliTest[2642:4831882] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-01 07:24:07.516 ThaliTest[2642:4831733] client: found new peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:07.517 ThaliTest[2642:4831733] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:07.518 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:07.519 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:24:07.519 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:08.513 ThaliTest[2642:4831733] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:24:09.348 ThaliTest[2642:4832748] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:09.350 ThaliTest[2642:4832748] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:09.350 ThaliTest[2642:4832748] client session: disconnect
2016-04-01 07:24:09.350 ThaliTest[2642:4832748] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:09.350 ThaliTest[2642:4832748] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:09.350 ThaliTest[2642:4832748] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:24:12.353 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:12.353 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:24:12.354 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:13.106 ThaliTest[2642:4832747] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:13.107 ThaliTest[2642:4832747] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:13.107 ThaliTest[2642:4832747] client session: disconnect
2016-04-01 07:24:13.107 ThaliTest[2642:4832747] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:13.108 ThaliTest[2642:4832747] client session: fireConnectCallb,ack: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:13.108 ThaliTest[2642:4832747] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 07:24:16.116 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:16.116 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:24:16.116 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:16.722 ThaliTest[2642:4832770] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:16.723 ThaliTest[2642:4832770] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:16.7,23 ThaliTest[2642:4832770] client session: disconnect
2016-04-01 07:24:16.723 ThaliTest[2642:4832770] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:16.723 ThaliTest[2642:4832770] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:16.723 ThaliTest[2642:4832770] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 7
,2016-04-01 07:24:19.729 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:19.729 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:24:19.730 ThaliTest[2642:4831882] client session: stateChange:0->,1 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:20.385 ThaliTest[2642:4832770] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:20.385 ThaliTest[2642:4832770] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:20.3,85 ThaliTest[2642:4832770] client session: disconnect
2016-04-01 07:24:20.385 ThaliTest[2642:4832770] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:20.386 ThaliTest[2642:4832770] client session: fireConnectCallb,ack: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:20.386 ThaliTest[2642:4832770] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 6
,2016-04-01 07:24:23.399 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:23.400 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:24:23.400 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:24.156 ThaliTest[2642:4832748] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:24.157 ThaliTest[2642:4832748] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:24.157 ThaliTest[2642:4832748] client session: disconnect
2016-04-01 07:24:24.157 ThaliTest[2642:4832748] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:24.158 ThaliTest[2642:4832748] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:24:24.158 ThaliTest[2642:4832748] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:24:27.161 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:24:27.161 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:24:27.162 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:24:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:24:27.521 ThaliTest[2642:4831733] client: found updated peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:27.522 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:27.522 ThaliTest[2642:4831733] client: found updated peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:24:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:24:47.535 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:47.535 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:24:47.536 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:00.126 ThaliTest[2642:4832891] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:00.126 ThaliTest[2642:4832891] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:00.1,26 ThaliTest[2642:4832891] client session: disconnect
2016-04-01 07:25:00.126 ThaliTest[2642:4832891] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:00.126 ThaliTest[2642:4832891] client session: fireConnectCallb,ack: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:00.126 ThaliTest[2642:4832891] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-04-01 07:25:03.136 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:25:03.136 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:25:03.136 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:04.208 ThaliTest[2642:4832892] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:04.208 ThaliTest[2642:4832892] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:04.208 ThaliTest[2642:4832892] client session: disconnect
2016-04-01 07:25:04.208 ThaliTest[2642:4832892] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:04.209 ThaliTest[2642:4832892] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:04.210 ThaliTest[2642:4832892] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 07:25:07.214 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:25:07.215 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:25:07.215 ThaliTest[2642:4831882] client session: stateChange:0->,1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:25:07.518 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:25:07.519 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:25:07.519 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:25:27.519 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:25:27.519 ThaliTest[2642:4831733] client: found updated peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:40.176 ThaliTest[2642:4832892] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:40.176 ThaliTest[2642:4832892] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:40.1,76 ThaliTest[2642:4832892] client session: disconnect
2016-04-01 07:25:40.176 ThaliTest[2642:4832892] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:40.176 ThaliTest[2642:4832892] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:40.176 ThaliTest[2642:4832892] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 07:25:43.188 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:25:43.188 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:25:43.189 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:43.813 ThaliTest[2642:4833012] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:43.814 ThaliTest[2642:4833012] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:43.814 ThaliTest[2642:4833012] client session: disconnect
2016-04-01 07:25:43.814 ThaliTest[2642:4833012] client session:, stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:43.815 ThaliTest[2642:4833012] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:43.815 ThaliTest[2642:4833012] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 07:25:46.821 ThaliTest[2642:4831882] jxcore: connect 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:25:46.821 ThaliTest[2642:4831882] client session: connect
2016-04-01 07:25:46.821 ThaliTest[2642:4831882] client session: stateChange:0->1 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:25:47.477 ThaliTest[2642:4833037] client session: not connected 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:47.478 ThaliTest[2642:4833037] client session: onLinkFailure: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:47.4,78 ThaliTest[2642:4833037] client session: disconnect
2016-04-01 07:25:47.478 ThaliTest[2642:4833037] client session: stateChange:1->0 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:25:47.478 ThaliTest[2642:4833037] client session: fireConnectCallback: 775127D1-BE71-46C7-B433-2FA7873DBB8C
2016-04-01 07:25:47.478 ThaliTest[2642:4833037] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,2016-04-01 07:25:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:25:47.527 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:25:47.528 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:47.528 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:26:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:26:07.768 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:07.768 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:07.768 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:26:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:27.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:27.52,1 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:26:47.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:26:47.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:47.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:27:07.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:07.522 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:07.523 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:27:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:27.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:27.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:27:47.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:27:47.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:47.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:28:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:28:27.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:28:27.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:47.503 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:28:47.519 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:28:47.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:47.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:29:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:29:07.519 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:07.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:29:07.52,0 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:29:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:29:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:29:27.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:29:27.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:29:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:29:47.523 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:47.523 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:29:47.52,3 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:30:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:30:07.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:30:07.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:30:07.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:30:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:30:27.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:30:27.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:30:27.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:30:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:30:47.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:30:47.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:30:47.522 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:31:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:31:07.525 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:07.526 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:31:07.526 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:31:27.503 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:31:27.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:31:27.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:31:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:31:47.523 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:47.523 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:31:47.523 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:32:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:32:07.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:07.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:07.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:32:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:32:27.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:27.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:27.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:32:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:32:47.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:47.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:32:47.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:33:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:33:07.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:33:07.522 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:07.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:33:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:33:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:33:27.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:33:27.52,1 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:33:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:33:47.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:33:47.523 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:33:47.523 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:34:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:34:07.519 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:34:07.523 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:34:07.524 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:34:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:34:27.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:34:27.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:34:27.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:34:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:34:47.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:34:47.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:34:47.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:35:07.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:07.521 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:35:07.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:35:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:35:27.519 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:35:27.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:35:27.522 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:35:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:35:47.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:35:47.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:35:47.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:36:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:36:07.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:36:07.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:36:07.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:36:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:36:27.528 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:36:27.528 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:36:27.530 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:36:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:36:47.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:36:47.520 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:36:47.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:37:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:37:07.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:37:07.523 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:07.524 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:37:27.522 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:27.522 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:37:27.523 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:37:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:37:47.519 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:37:47.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:37:47.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:38:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:38:07.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:38:07.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:07.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:27.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:38:27.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:38:27.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:27.52,2 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:47.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:38:47.521 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:38:47.521 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:47.52,1 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:39:07.504 ThaliTest[2642:4831733] multipeer manager: restart client
,2016-04-01 07:39:07.520 ThaliTest[2642:4831733] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:39:07.520 ThaliTest[2642:4831733] client: found existing peer: 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:39:07.523 ThaliTest[2642:4831733] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9

```
