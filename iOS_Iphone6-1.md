#### Test 639808779d5bfaa_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5E026584-C20E-4DB4-9583-08D8335218A6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5E026584-C20E-4DB4-9583-08D8335218A6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639808779d5bfaa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56332"
,(lldb)     command script import "/tmp/5E026584-C20E-4DB4-9583-08D8335218A6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 11:04:44.586 ThaliTest[2352:4362279] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7E55593A-5353-42FA-8CF5-52B435C8EB35/Library/Cookies/Cookies.binarycookies
,2016-03-29 11:04:44.826 ThaliTest[2352:4362279] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 11:04:44.827 ThaliTest[2352:4362279] Multi-tasking -> Device: YES, App: YES
,2016-03-29 11:04:44.844 ThaliTest[2352:4362279] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 11:04:45.632 ThaliTest[2352:4362279] Using UIWebView
2016-03-29 11:04:45.634 ThaliTest[2352:4362279] [CDVTimer][handleopenurl] 0.114024ms
2016-03-29 11:04:45.636 ThaliTest[2352:4362279] [CDVTimer][intentandnavigationfilter] 2.116978ms
2016-03,-29 11:04:45.636 ThaliTest[2352:4362279] [CDVTimer][gesturehandler] 0.096023ms
2016-03-29 11:04:45.636 ThaliTest[2352:4362279] [CDVTimer][TotalPluginStartup] 2.752006ms
,2016-03-29 11:04:48.748 ThaliTest[2352:4362279] Resetting plugins due to page load.
,2016-03-29 11:04:50.160 ThaliTest[2352:4362279] Finished load of: file:///var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/index.html
,2016-03-29 11:04:50.328 ThaliTest[2352:4362279] JXcore Cordova plugin initializing
2016-03-29 11:04:50.331 ThaliTest[2352:4362454] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-29 11:04:57.277 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:04:57.277 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:04:57.278 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:04:57.280 ThaliTest[2352:4362454] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/796C05D8-75BF-43E6-BA61-D1F0C032CF0C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53474
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53476
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
DEBUG createNativeListener: listening 53479
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53483
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
DEBUG createNativeListener: listening 53488
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
DEBUG createNativeListener: listening 53492
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
DEBUG createNativeListener: listening 53496
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 53500
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
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53504
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new ,mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNat,iveListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG cr,eateNativeListener: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG ,createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG cr,eateNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG crea,teNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
,ok 29 native server should be closed
ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
D,EBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53556
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
DEBUG createNativeListener: listening 53560
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
ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
,# teardown
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
,ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
# teardown
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
,ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53572
2016-03-29 11:07:29.414 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.415 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-29 11:07:29.416 ThaliTest[2352:4362454] jx,core: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.416 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-29 11:07:29.638 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:29.638 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:07:29.638 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:07:29.638 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:29.639 ThaliTest[2352,:4362454] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53574
2016-03-29 11:07:29.909 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
,2016-03-29 11:07:29.910 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:07:29.911 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 11:07:29.919 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:07:29.919 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-29 11:07:30.675 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:30.675 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:07:30.676 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:07:30.676 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:07:30.676 ThaliTest[2352:4362454] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:30.676 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 99 error should be null
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53576
,2016-03-29 11:07:32.393 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:07:32.393 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:1
,2016-03-29 11:07:32.395 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
2016-03-29 11:07:32.395 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:1
2016-03-29 11:07:32.395 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
,2016-03-29 11:07:32.413 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:07:32.413 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:07:32.413 ThaliTest[2352:4362454] multipeer manager: stop client ti,mer
2016-03-29 11:07:32.413 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:2
2016-03-29 11:07:32.414 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
2016-03-29 11:07:32.414 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:2
2016-03-29 11:07:32.414 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,# teardown
,2016-03-29 11:07:39.537 ThaliTest[2352:4362279] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:07:41.330 ThaliTest[2352:4362279] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
,2016-03-29 11:07:45.340 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:07:45.341 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:07:45.341 ThaliTest[2352:4362454] multipeer manager: stop client timer
20,16-03-29 11:07:45.341 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:07:45.341 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 11:07:45.342 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 105 error should be null
ok 106 error should be null
# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53581
2016-03-29 11:08:46.284 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.285 ThaliTest[2352:4362454] THEMultipeerManager stoppi,ng peer
2016-03-29 11:08:46.285 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-29 11:08:46.286 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.286 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:08:46.286 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
ok 110 error should be null
# teardown
,2016-03-29 11:08:46.474 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.475 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:08:46.475 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:08:46.475 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:46.475 ThaliTest[2352,:4362454] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53583
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-29 11:08:46.909 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:46.909 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:08:46.909 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:08:46.909 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:46.910 ThaliTest[2352,:4362454] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53585
2016-03-29 11:08:47.180 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
2016-03-29 11:08:47.181 ThaliTest[2352:4362454] multipeer manager: sta,rt client restart timer: 0x15ef3770
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:08:47.181 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
,2016-03-29 11:08:47.187 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:08:47.187 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:3
2016-03-29 11:08:47.187 ThaliTest[2352:4362454] THEMultipee,rManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:3
2016-03-29 11:08:47.187 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 118 called only once
ok 119 discovery state matches
ok 120 advertising state matches
# teardown
,2016-03-29 11:08:47.425 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:08:47.425 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
,2016-03-29 11:08:47.425 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:08:47.426 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:08:47.426 ThaliTest[2352:4362454] multipeer manager: stop cl,ient timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:08:47.426 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 121 error should be null
,ok 122 error should be null
,# setup
,# 32. does not send duplicate availability changes
,ok 123 should be called once
ok 124 should not have been called more than once
# teardown
,ok 125 error should be null
ok 126 error should be null
# setup
,# 33. can get the network status
,ok 127 network status should have certain non-empty properties
# teardown
,ok 128 error should be null
ok 129 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 130 host address should match
ok 131 port should match
,ok 132 host address should be null
,ok 133 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-29 11:09:40.333 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
2016-03-29 11:09:40.334 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:09:40.336 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAd,vertisements without error
2016-03-29 11:09:40.337 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:09:40.337 ThaliTest[2352:4362454] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:09:40.337 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 11:09:40.581 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:09:40.582 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:09:40.582 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:09:40.582 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:09:40.582 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 11:10:03.287 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
2016-03-29 11:10:03.287 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:10:03.287 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 11:10:03.288 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:10:03.289 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 11:10:14.875 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:10:14.875 ThaliTest[2352:4362454] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:10:14.876 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:14.877 ThaliTest[2352:43624,54] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:14.877 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:10:14.877 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-29 11:10:25.304 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:25.304 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:4
2016-03-29 11:10:25.304 ThaliTest[2352:4362454] multipeer m,anager: start client restart timer: 0x15ef3770
2016-03-29 11:10:25.304 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:4
2016-03-29 11:10:25.305 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 144 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:10:25.305 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:25.305 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
,2016-03-29 11:10:25.305 ThaliTest[2352:4362454] multipeer manager: stop client timer
2016-03-29 11:10:25.310 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 145 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-29 11:10:28.433 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:10:28.433 ThaliTest[2352:43624,54] jxcore: stopListeningForAdvertisements: success
ok 146 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:28.434 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:28.434 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:10:28.434 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 147 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-29 11:10:55.281 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.281 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:5
2016-03-29 11:10:55.282 ThaliTest[2352:4362454] multipeer m,anager: start client restart timer: 0x15ef3770
2016-03-29 11:10:55.282 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:5
,2016-03-29 11:10:55.285 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:10:55.285 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.286 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:10:55.286 ThaliTest[2352:4362454] multipeer manager: stop client timer
2016-03-29 11:10:55.286 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-,A4B5-8A232A1C6437:6
2016-03-29 11:10:55.286 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
2016-03-29 11:10:55.286 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:6
,2016-03-29 11:10:55.286 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 149 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-29 11:10:55.524 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:10:55.525 ThaliTest[2352:436245,4] jxcore: stopListeningForAdvertisements: success
ok 150 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:10:55.525 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:10:55.526 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:10:55.526 ThaliTest[2352:4362454] multipeer manager: stop client timer
2016-03-29 11:10:55.526 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. peerAvailabilityChange is called
,2016-03-29 11:10:55.750 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:10:55.751 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:10:55.751 ThaliTest[2352:4362454] multipeer m,Active":true,"discoveryActive":true}
2016-03-29 11:10:55.752 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 153 Can call startListeningForAdvertisements without error
anager: start client restart timer: 0x15ef3770
2016-03-29 11:10:55.751 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:7
2016-03-29 11:10:55.751 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 152 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-29 11:10:55.752 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,2016-03-29 11:10:56.943 ThaliTest[2352:4362279] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:2
ok 154 peers must be an array
ok 155 peers must not be zero-length
ok 156 peer must have peerIdentifier
ok 157 peerIdentifier must be a strin,g
ok 158 peer must have peerAvailable
ok 159 peer must have pleaseConnect
,# teardown
,2016-03-29 11:10:57.341 ThaliTest[2352:4362279] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:2
,2016-03-29 11:11:06.719 ThaliTest[2352:4362279] client: lost peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:11:06.719 ThaliTest[2352:4362279] client session: onPeerLost: CF5927A1-42FA-4DDF-8112-8BFA72204E68
,2016-03-29 11:11:15.752 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:11:15.759 ThaliTest[2352:4362279] client: found updated peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:32.777 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 11:11:32.778 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 11:11:32.779 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
,2016-03-29 11:11:32.779 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:11:32.779 ThaliTest[2352:4362454] multipeer manager: stop client timer
2016-03-29 11:11:32.779 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-29 11:11:33.223 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:11:33.223 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:11:33.223 ThaliTest[2352:4362454] multipeer m,anager: start client restart timer: 0x15ef3770
2016-03-29 11:11:33.224 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:8
2016-03-29 11:11:33.224 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 162 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:11:33.224 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-29 11:11:33.225 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 163 Can call startListeningForAdvertisements without error
,2016-03-29 11:11:33.893 ThaliTest[2352:4362279] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7","pleaseConnect":0}]
2016-03-29 11:11:33.894 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:33.894 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:33.894 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:34.030 ThaliTest[2352:4362279] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CF5927A1-42FA-4DDF-8112-8BFA72204E68:7","pleaseConnect":0}]
,2016-03-29 11:11:35.657 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:11:35.658 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232,A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:11:37.109 ThaliTest[2352:4363285] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:37.109 ThaliTest[2352:4363285] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:37.1,09 ThaliTest[2352:4363285] client session: disconnect
2016-03-29 11:11:37.109 ThaliTest[2352:4363285] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:37.109 ThaliTest[2352:4363285] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:37.110 ThaliTest[2352:4363285] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 11:11:40.113 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:40.113 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:40.113 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:40.610 ThaliTest[2352:4363324] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:40.610 ThaliTest[2352:4363324] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:40.6,10 ThaliTest[2352:4363324] client session: disconnect
2016-03-29 11:11:40.610 ThaliTest[2352:4363324] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:40.611 ThaliTest[2352:4363324] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:40.612 ThaliTest[2352:4363324] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 11:11:43.614 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:43.615 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:43.615 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:44.998 ThaliTest[2352:4363285] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:44.999 ThaliTest[2352:4363285] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:44.9,99 ThaliTest[2352:4363285] client session: disconnect
2016-03-29 11:11:44.999 ThaliTest[2352:4363285] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:44.999 ThaliTest[2352:4363285] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:45.000 ThaliTest[2352:4363285] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 11:11:46.481 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:11:46.481 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:11:46.481 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:11:48.011 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:48.012 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:48.012 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:48.873 ThaliTest[2352:4363324] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:48.873 ThaliTest[2352:4363324] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:48.8,73 ThaliTest[2352:4363324] client session: disconnect
2016-03-29 11:11:48.873 ThaliTest[2352:4363324] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:48.873 ThaliTest[2352:4363324] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:48.873 ThaliTest[2352:4363324] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 11:11:51.882 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:51.882 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:51.882 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:52.426 ThaliTest[2352:4363286] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:52.426 ThaliTest[2352:4363286] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:52.426 ThaliTest[2352:4363286] client session: disconnect
2016-03-29 11:11:52.426 ThaliTest[2352:4363286] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:52.426 ThaliTest[2352:4363286] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:52.427 ThaliTest[2352:4363286] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 5
,2016-03-29 11:11:53.225 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:11:53.233 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:53.233 ThaliTest[2352:4362279] client: found updated peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CF5927A1-42FA-4DDF-8112-8BFA72204E68:8","pleaseConnect":0}]
,2016-03-29 11:11:55.431 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:55.432 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:55.432 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:55.909 ThaliTest[2352:4363327] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:55.909 ThaliTest[2352:4363327] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
,2016-03-29 11:11:55.910 ThaliTest[2352:4363327] client session: disconnect
,2016-03-29 11:11:55.910 ThaliTest[2352:4363327] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:55.910 ThaliTest[2352:4363327] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
,2016-03-29 11:11:55.912 ThaliTest[2352:4363327] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 11:11:58.915 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:58.915 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:11:58.915 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:59.513 ThaliTest[2352:4363285] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:11:59.513 ThaliTest[2352:4363285] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:59.513 ThaliTest[2352:4363285] client session: disconnect
2016-03-29 11:11:59.513 ThaliTest[2352:4363285] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:11:59.515 ThaliTest[2352:4363285] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:11:59.515 ThaliTest[2352:4363285] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 11:11:59.585 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:11:59.585 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:11:59.585 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:12:02.529 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:02.529 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:12:02.530 ThaliTest[2352:4362454] client session: stateChange:0->,1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:12:03.133 ThaliTest[2352:4363324] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:03.133 ThaliTest[2352:4363324] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:12:03.133 ThaliTest[2352:4363324] client session: disconnect
2016-03-29 11:12:03.133 ThaliTest[2352:4363324] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:03.133 ThaliTest[2352:4363324] client session: fireConnectCallb,ack: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:12:03.133 ThaliTest[2352:4363324] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 11:12:06.142 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:06.142 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:12:06.142 ThaliTest[2352:4362454] client session: stateChange:0->,1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:12:06.798 ThaliTest[2352:4363286] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:12:06.799 ThaliTest[2352:4363286] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:12:06.799 ThaliTest[2352:4363286] client session: disconnect
2016-03-29 11:12:06.800 ThaliTest[2352:4363286] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:06.800 ThaliTest[2352:4363286] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:12:06.800 ThaliTest[2352:4363286] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 11:12:09.802 ThaliTest[2352:4362454] jxcore: connect AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:09.802 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:12:09.802 ThaliTest[2352:4362454] client session: stateChange:0->1 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:12:10.451 ThaliTest[2352:4363285] client session: not connected AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:10.451 ThaliTest[2352:4363285] client session: onLinkFailure: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:12:10.4,51 ThaliTest[2352:4363285] client session: disconnect
2016-03-29 11:12:10.451 ThaliTest[2352:4363285] client session: stateChange:1->0 AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:10.451 ThaliTest[2352:4363285] client session: fireConnectCallback: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB
2016-03-29 11:12:10.452 ThaliTest[2352:4363285] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 164 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-29 11:12:12.707 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:12:12.707 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:12:12.707 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:12:13.225 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:12:13.233 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:13.233 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:27.346 ThaliTest[2352:4362279] multipeer session: reset timer
,2016-03-29 11:12:27.347 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
,2016-03-29 11:12:27.347 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:12:33.225 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:12:33.235 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:33.235 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:12:39.586 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:12:39.587 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:12:39.587 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:12:51.468 ThaliTest[2352:4362279] multipeer session: reset timer
,2016-03-29 11:12:51.469 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:12:51.469 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:12:53.224 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:12:53.235 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:12:53.236 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:06.004 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:13:06.004 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:13:06.004 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:13:13.225 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:13:13.237 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:13:13.237 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:17.884 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:13:17.884 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:13:17.884 ThaliTest[2352:4362279], server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:13:30.729 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:13:30.730 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:13:30.730 ThaliTest[2352:4362279], server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:8 != F067257C-7084-41CC-A4B5-8A232A1C6437:7)
,2016-03-29 11:13:33.225 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:13:33.237 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
2016-03-29 11:13:33.237 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:42.424 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-29 11:13:42.425 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 11:13:42.426 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:13:42.426 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:13:42.426 ThaliTest[2352:4362454] multipeer manager: stop client timer
20,16-03-29 11:13:42.426 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 166 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-29 11:13:42.783 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:13:42.783 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:13:42.783 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
2016-03-29 11:13:42.783 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:9
2016-03-29 11:13:42.783 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 167 Can call startUpdateAdvertisingAndListening without error
2016-03-29 11:13:42.784 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-29 11:13:42.785 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
,ok 168 Can call startListeningForAdvertisements without error
,2016-03-29 11:13:43.541 ThaliTest[2352:4362279] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:43.542 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:43.542 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:13:43.542 ThaliTest[2352:4362454] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:43.548 ThaliTest[2352:4362279] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:7
,2016-03-29 11:13:44.771 ThaliTest[2352:4363789] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:44.771 ThaliTest[2352:4363789] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:44.772 ThaliTest[2352:4363789] client session: disconnect
2016-03-29 11:13:44.772 ThaliTest[2352:4363789] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:44.773 ThaliTest[2352:4363789] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:44.773 ThaliTest[2352:4363789] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-29 11:13:45.797 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:13:45.797 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:9 != F067257C-7084-41CC-A4B5-8A232A1C6437:8)
,2016-03-29 11:13:47.784 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:47.785 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:13:47.785 ThaliTest[2352:4362454] client session: stateChange:0->,1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:47.980 ThaliTest[2352:4363789] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:47.981 ThaliTest[2352:4363789] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:47.981 ThaliTest[2352:4363789] client session: disconnect
2016-03-29 11:13:47.981 ThaliTest[2352:4363789] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:47.981 ThaliTest[2352:4363789] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:47.981 ThaliTest[2352:4363789] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-29 11:13:50.991 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:50.991 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:13:50.992 ThaliTest[2352:4362454] client session: stateChange:0->,1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:51.158 ThaliTest[2352:4363789] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:51.159 ThaliTest[2352:4363789] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:51.1,59 ThaliTest[2352:4363789] client session: disconnect
2016-03-29 11:13:51.159 ThaliTest[2352:4363789] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:51.160 ThaliTest[2352:4363789] client session: fireConnectCallb,ack: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:51.160 ThaliTest[2352:4363789] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-29 11:13:54.171 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:54.171 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:13:54.171 ThaliTest[2352:4362454] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:54.271 ThaliTest[2352:4363789] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:54.272 ThaliTest[2352:4363789] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:54.272 ThaliTest[2352:4363789] client session: disconnect
2016-03-29 11:13:54.272 ThaliTest[2352:4363789] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:54.272 ThaliTest[2352:4363789] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:54.272 ThaliTest[2352:4363789] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-29 11:13:57.285 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:57.285 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:13:57.285 ThaliTest[2352:4362454] client session: stateChange:0->,1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:13:57.430 ThaliTest[2352:4363789] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:57.430 ThaliTest[2352:4363789] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:57.4,30 ThaliTest[2352:4363789] client session: disconnect
2016-03-29 11:13:57.430 ThaliTest[2352:4363789] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:13:57.430 ThaliTest[2352:4363789] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:13:57.430 ThaliTest[2352:4363789] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 5
,2016-03-29 11:13:57.921 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:13:57.921 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:13:57.921 ThaliTest[2352:4362279], server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:9 != F067257C-7084-41CC-A4B5-8A232A1C6437:8)
,2016-03-29 11:14:00.437 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:00.437 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:14:00.437 ThaliTest[2352:4362454] client session: stateChange:0->,1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
,2016-03-29 11:14:00.591 ThaliTest[2352:4363716] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:00.591 ThaliTest[2352:4363716] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:00.5,91 ThaliTest[2352:4363716] client session: disconnect
2016-03-29 11:14:00.591 ThaliTest[2352:4363716] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:00.591 ThaliTest[2352:4363716] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:00.591 ThaliTest[2352:4363716] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-29 11:14:02.784 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:14:02.797 ThaliTest[2352:4362279] client: found updated peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
2016-03-29 11:14:02.797 ThaliTest[2352:4362279] client: found updated peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:03.599 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:03.600 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:14:03.600 ThaliTest[2352:4362454] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:03.744 ThaliTest[2352:4363716] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:03.746 ThaliTest[2352:4363716] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:03.7,46 ThaliTest[2352:4363716] client session: disconnect
2016-03-29 11:14:03.746 ThaliTest[2352:4363716] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:03.746 ThaliTest[2352:4363716] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:03.746 ThaliTest[2352:4363716] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-29 11:14:06.759 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:06.759 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:14:06.759 ThaliTest[2352:4362454] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:06.934 ThaliTest[2352:4363828] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:06.935 ThaliTest[2352:4363828] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:06.935 ThaliTest[2352:4363828] client session: disconnect
2016-03-29 11:14:06.935 ThaliTest[2352:4363828] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:06.937 ThaliTest[2352:4363828] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:06.937 ThaliTest[2352:4363828] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-29 11:14:09.946 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:09.946 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:14:09.947 ThaliTest[2352:4362454] client session: stateChange:0->1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:09.983 ThaliTest[2352:4363829] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:09.983 ThaliTest[2352:4363829] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:09.9,83 ThaliTest[2352:4363829] client session: disconnect
2016-03-29 11:14:09.984 ThaliTest[2352:4363829] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:09.984 ThaliTest[2352:4363829] client session: fireConnectCallb,ack: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:09.984 ThaliTest[2352:4363829] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-29 11:14:10.976 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:14:10.977 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:14:10.977 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:9 != F067257C-7084-41CC-A4B5-8A232A1C6437:8)
,2016-03-29 11:14:12.994 ThaliTest[2352:4362454] jxcore: connect CF5927A1-42FA-4DDF-8112-8BFA72204E68:8
2016-03-29 11:14:12.994 ThaliTest[2352:4362454] client session: connect
2016-03-29 11:14:12.994 ThaliTest[2352:4362454] client session: stateChange:0->,1 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:13.244 ThaliTest[2352:4363789] client session: not connected CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:13.244 ThaliTest[2352:4363789] client session: onLinkFailure: CF5927A1-42FA-4DDF-8112-8BFA72204E68
2016-03-29 11:14:13.244 ThaliTest[2352:4363789] client session: disconnect
2016-03-29 11:14:13.244 ThaliTest[2352:4363789] client session: stateChange:1->0 CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:13.246 ThaliTest[2352:4363789] client session: fireConnectCallback: CF5927A1-42FA-4DDF-8112-8BFA72204E68
,2016-03-29 11:14:13.246 ThaliTest[2352:4363789] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 169 Connect failed!
,  ---
,    operator: fail
  ...
,# teardown
,2016-03-29 11:14:22.784 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:14:22.792 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:14:22.793 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:14:42.784 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:14:42.797 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:14:42.797 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:14:46.977 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:14:46.977 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:14:46.977 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:9 != F067257C-7084-41CC-A4B5-8A232A1C6437:8)
,2016-03-29 11:14:59.815 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:14:59.815 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:14:59.815 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:9 != F067257C-7084-41CC-A4B5-8A232A1C6437:8)
,2016-03-29 11:15:02.784 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:15:02.793 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
2016-03-29 11:15:02.794 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
,2016-03-29 11:15:12.888 ThaliTest[2352:4362279] multipeer session: reset timer
2016-03-29 11:15:12.889 ThaliTest[2352:4362279] server: disconnecting to refresh session (CF5927A1-42FA-4DDF-8112-8BFA72204E68)
2016-03-29 11:15:12.889 ThaliTest[2352:4362279] server: rejecting invitation from CF5927A1-42FA-4DDF-8112-8BFA72204E68 due to previous generation (F067257C-7084-41CC-A4B5-8A232A1C6437:9 != F067257C-7084-41CC-A4B5-8A232A1C6437:8)
,2016-03-29 11:15:22.156 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-29 11:15:22.157 ThaliTest[2352:436245,4] jxcore: stopListeningForAdvertisements: success
ok 170 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 11:15:22.158 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:22.158 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:22.158 ThaliTest[2352:4362454] multipeer manager: stop client timer
2016-03-29 11:15:22.158 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 171 Should be able to call stopAdvertisingAndListening in teardown
# setup
,2016-03-29 11:15:23.945 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:23.945 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:23.946 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:23.947 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. #startListeningForAdvertisements should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-29 11:15:24.415 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:24.415 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:24.415 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:24.416 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 173 specific error should be returned
,# teardown
,# setup
,2016-03-29 11:15:25.471 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:25.471 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:25.471 ThaliTest[2352:4,362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:15:25.472 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53631
,2016-03-29 11:15:25.824 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:25.825 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,ok 174 no errors
,2016-03-29 11:15:25.826 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:25.827 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,ok 175 still no errors
,# teardown
,2016-03-29 11:15:26.096 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:26.096 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:26.096 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:15:26.096 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:26.097 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:26.262 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:26.262 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:26.263 ThaliTest[2352:4,362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:26.264 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53633
2016-03-29 11:15:26.476 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
2016-03-29 11:15:26.476 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:15:26.477 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 176 no errors
2016-03-29 11:15:26.478 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:15:26.479 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
ok 177 still no errors
# teardown
,2016-03-29 11:15:26.709 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:26.709 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:26.709 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:15:26.709 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:15:26.709 ThaliTest[2352:4362454] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:15:26.710 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
# setup
,2016-03-29 11:15:26.904 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:26.904 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:26.904 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:26.905 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53635
,2016-03-29 11:15:27.101 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:15:27.101 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:10
2016-03-29 11:15:27.101 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
2016-03-29 11:15:27.101 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:10
,2016-03-29 11:15:27.102 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 178 no errors
2016-03-29 11:15:27.103 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:15:27.103 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:27.104 ThaliTest[2352:4362454] multipeer manager: stop client timer
,2016-03-29 11:15:27.104 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:11
,2016-03-29 11:15:27.104 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
2016-03-29 11:15:27.106 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:11
2016-03-29 11:15:27.107 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
ok 179 still no errors
# teardown
,2016-03-29 11:15:27.218 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:27.219 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:27.219 ThaliTest[2352:4362454] multipeer manager: stop client timer
20,16-03-29 11:15:27.219 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:15:27.219 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:27.220 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:27.379 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 11:15:27.380 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 11:15:27.381 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:27.382 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53639
,2016-03-29 11:15:27.912 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:27.913 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:27.913 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 180 no errors
,2016-03-29 11:15:27.913 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:27.914 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:27.914 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
ok 181 still no errors
,# teardown
,2016-03-29 11:15:28.363 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:15:28.363 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:15:28.363 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:15:28.364 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 11:15:28.364 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:15:29.938 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:15:29.939 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:15:29.939 ThaliTest[2352:4,362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:15:29.940 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. can get the network status before starting
,ok 182 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-29 11:16:15.084 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:15.084 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:15.084 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:16:15.085 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 49. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ok 183 specific error expected
# teardown
,# setup
,2016-03-29 11:16:15.683 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:15.683 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:15.683 ThaliTest[2352:4,362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:16:15.684 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 50. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53641
2016-03-29 11:16:16.170 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
2016-03-29 11:16:16.171 ThaliTest[2352:4362454] multipeer manager: sta,rt client restart timer: 0x15ef3770
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 11:16:16.171 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
2016-03-29 11:16:16.172 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:16:16.172 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:12
2016-03-29 11:16:16.172 ThaliTest[2352:4362454] THEMulti,peerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:12
2016-03-29 11:16:16.172 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 184 connection to servers manager should succeed after starting
,ok 185 connection to router server should succeed after starting
2016-03-29 11:16:16.204 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:16:16.204 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:16:16.20,4 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:16:16.205 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:16:16.205 ThaliTest[2352:4362454] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:16:16.206 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
DEBUG createNativeListener: mux close
ok 186 is stopped after calling stop
DEBUG createNativeListener: incoming socket close
,ok 187 connection to servers manager should fail after stopping
,ok 188 connection to router server should fail after stopping
# teardown
,# setup
,2016-03-29 11:16:19.789 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:19.789 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:19.789 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:16:19.790 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure terminateConnection is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-29 11:16:57.885 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:16:57.885 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:16:57.886 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:16:57.887 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. make sure terminateListener is properly hooked up
,ok 190 called with right arguments
,# teardown
,# setup
,2016-03-29 11:17:01.000 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:01.000 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:01.000 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-29 11:17:01.001 ThaliTest[2352:4362454] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 53. make sure we actually call kill connections properly
,2016-03-29 11:17:01.605 ThaliTest[2352:4362454] jxcore: killConnections
2016-03-29 11:17:01.605 ThaliTest[2352:4362454] jxcore: killConnections: badParam
,not ok 191 should not fail on iOS
,  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-29 11:17:02.048 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:02.048 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:02.048 ThaliTest[2352:4,362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:02.050 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53648
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":53647,"error":{}}
,2016-03-29 11:17:02.490 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:02.491 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:17:02.491 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 11:17:02.491 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:17:02.491 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,ok 192 failure reason is as expected
,ok 193 error description is as expected
,ok 194 must be stopped
,# teardown
,# setup
,2016-03-29 11:17:05.772 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:05.773 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:05.773 ThaliTest[2352:4362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:05.774 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 55. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53650
,ok 195 peerIdentifier matches
,ok 196 error description matches
,# teardown
,2016-03-29 11:17:13.457 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:13.457 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:17:13.457 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:17:13.457 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 11:17:13.458 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-29 11:17:14.684 ThaliTest[2352:4362454] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-29 11:17:14.684 ThaliTest[2352:4362454] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-29 11:17:14.685 ThaliTest[2352:4,362454] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 11:17:14.686 ThaliTest[2352:4362454] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 56. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53652
,2016-03-29 11:17:14.894 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements
2016-03-29 11:17:14.894 ThaliTest[2352:4362454] multipeer manager: start client restart timer: 0x15ef3770
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 197 discoveryActive matches
ok 198 advertisingActive matches
2016-03-29 11:17:14.896 ThaliTest[2352:4362454] jxcore: startListeningForAdvertisements: success
,2016-03-29 11:17:14.899 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening
2016-03-29 11:17:14.899 ThaliTest[2352:4362454] THEMultipeerManager stopping peer
2016-03-29 11:17:14.899 ThaliTest[2352:4362454] jxcore: stopAdvertisingAndListening: success
2016-03-29 11:17:14.899 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements
2016-03-29 11:17:14.899 ThaliTest[2352:4362454] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
ok 199 discoveryActive matches
,ok 200 advertisingActive matches
2016-03-29 11:17:14.901 ThaliTest[2352:4362454] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53654
,2016-03-29 11:17:14.907 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening
2016-03-29 11:17:14.907 ThaliTest[2352:4362454] server: starting F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:17:14.907 ThaliTest[2352:4362454] multipeer ,manager: start client restart timer: 0x15ef3770
2016-03-29 11:17:14.907 ThaliTest[2352:4362454] THEMultipeerManager initialized peer F067257C-7084-41CC-A4B5-8A232A1C6437:13
2016-03-29 11:17:14.907 ThaliTest[2352:4362454] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-29 11:17:16.867 ThaliTest[2352:4362279] client: found new peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:9
2016-03-29 11:17:16.867 ThaliTest[2352:4362279] client: found new peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:9
,2016-03-29 11:17:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:17:34.918 ThaliTest[2352:4362279] client: found updated peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:17:34.918 ThaliTest[2352:4362279] client: found updated peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:17:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:17:54.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:17:54.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:18:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:18:14.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:18:14.918 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:18:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:18:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:18:34.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:18:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:18:54.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:18:54.919 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:19:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:19:14.918 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:19:14.918 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:19:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:19:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:19:34.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:19:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:19:54.916 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:19:54.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:20:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:20:14.920 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:20:14.920 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:20:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:20:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:20:34.918 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:20:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:20:54.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:20:54.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:21:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:21:14.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:21:14.918 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:21:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:21:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:21:34.918 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:21:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:21:54.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:21:54.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:22:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:22:14.922 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:22:14.922 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:22:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:22:34.920 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:22:34.920 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:22:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:22:54.918 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:22:54.919 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:23:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:23:14.922 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:23:14.922 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:23:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:23:34.916 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:23:34.916 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:23:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:23:54.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:23:54.918 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:24:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:24:14.918 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:24:14.919 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:24:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:24:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:24:34.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:24:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:24:54.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:24:54.918 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:25:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:25:14.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:25:14.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:25:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:25:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:25:34.918 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:25:54.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:25:54.918 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:25:54.919 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
,2016-03-29 11:26:14.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:26:14.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13
2016-03-29 11:26:14.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
,2016-03-29 11:26:34.908 ThaliTest[2352:4362279] multipeer manager: restart client
,2016-03-29 11:26:34.917 ThaliTest[2352:4362279] client: found existing peer: CF5927A1-42FA-4DDF-8112-8BFA72204E68:13
2016-03-29 11:26:34.917 ThaliTest[2352:4362279] client: found existing peer: AAA6A3C2-4C66-4755-8AC6-E775E23EAFBB:13

```
