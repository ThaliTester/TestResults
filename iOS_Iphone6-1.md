#### Test 6391070405f2a33_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/228DA601-BE0D-4195-9379-E6BF6329526A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/228DA601-BE0D-4195-9379-E6BF6329526A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55613"
,(lldb)     command script import "/tmp/228DA601-BE0D-4195-9379-E6BF6329526A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:26:45.693 ThaliTest[2096:3652008] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F4286024-CBC1-4A8D-9104-B87C174E7407/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:26:45.960 ThaliTest[2096:3652008] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:26:45.961 ThaliTest[2096:3652008] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:26:45.978 ThaliTest[2096:3652008] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:26:46.807 ThaliTest[2096:3652008] Using UIWebView
,2016-03-24 15:26:46.810 ThaliTest[2096:3652008] [CDVTimer][handleopenurl] 0.234008ms
2016-03-24 15:26:46.812 ThaliTest[2096:3652008] [CDVTimer][intentandnavigationfilter] 2.353966ms
2016-03-24 15:26:46.812 ThaliTest[2096:3652008] [CDVTimer][gesturehandle,r] 0.118017ms
2016-03-24 15:26:46.813 ThaliTest[2096:3652008] [CDVTimer][TotalPluginStartup] 3.318965ms
,2016-03-24 15:26:50.146 ThaliTest[2096:3652008] Resetting plugins due to page load.
,2016-03-24 15:26:51.629 ThaliTest[2096:3652008] Finished load of: file:///var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/index.html
,2016-03-24 15:26:51.816 ThaliTest[2096:3652008] JXcore Cordova plugin initializing
,2016-03-24 15:26:51.819 ThaliTest[2096:3652155] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:27:01.983 ThaliTest[2096:3652155] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 15:27:01.984 ThaliTest[2096:3652155] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-24 15:27:01.985 ThaliTest[2096:3652155] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 15:27:01.987 ThaliTest[2096:3652155] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/358068C4-BBBE-40DF-A91E-00E76E5468B6/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51465
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51467
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
,DEBUG createNativeListener: listening 51470
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
,DEBUG createNativeListener: listening 51474
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
,DEBUG createNativeListener: listening 51479
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
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51483
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51487
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51491
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51495
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
DEBUG createNativeListener: listening 51547
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
,DEBUG createNativeListener: listening 51551
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
,# teardown
,# setup
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# teardown
,# setup
,# 16. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 19. basic
,ok 74 sane
,# teardown
,# setup
,# 20. another
,ok 75 sane
,# teardown
,# setup
,# 21. can pass data in setup
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,# teardown
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,ok 82 specific error should be returned
,# teardown
,ok 83 error should be null
,ok 84 error should be null
,# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51563
2016-03-24 15:29:34.548 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false},
2016-03-24 15:29:34.549 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 15:29:34.551 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
DEBUG thaliMob,ileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:34.552 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 15:29:34.657 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:34.657 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:29:34.657 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:29:34.657 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:34.658 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51565
,2016-03-24 15:29:34.932 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements
,2016-03-24 15:29:34.934 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 15:29:34.935 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-24 15:29:34.943 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 15:29:34.945 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-24 15:29:35.174 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:35.174 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:29:35.174 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:29:35.175 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
2016-03-24 15:29:35.175 ThaliTest[2096:3652155] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:35.176 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be n,ull
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51567
,2016-03-24 15:29:35.715 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:29:35.715 ThaliTest[2096:3652155] server: starting DD1A9DF3-8261-4279-BA77-CCA8E9F37311:1
2016-03-24 15:29:35.716 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
2016-03-24 15:29:35.716 ThaliTest[2096:3652155] THEMultipeerManager initialized peer DD1A9DF3-8261-4279-BA77-CCA8E9F37311:1
2016-03-24 15:29:35.716 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-24 15:29:35.724 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:29:35.725 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
,2016-03-24 15:29:35.727 ThaliTest[2096:3652155] multipeer manager: stop client timer
,2016-03-24 15:29:35.730 ThaliTest[2096:3652155] server: starting DD1A9DF3-8261-4279-BA77-CCA8E9F37311:2
,2016-03-24 15:29:35.735 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
,2016-03-24 15:29:35.736 ThaliTest[2096:3652155] THEMultipeerManager initialized peer DD1A9DF3-8261-4279-BA77-CCA8E9F37311:2
,2016-03-24 15:29:35.736 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-24 15:29:35.902 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
,2016-03-24 15:29:35.903 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
,2016-03-24 15:29:35.904 ThaliTest[2096:3652155] multipeer manager: stop client timer
,2016-03-24 15:29:35.906 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
,2016-03-24 15:29:35.907 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:29:35.909 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51572
,2016-03-24 15:29:53.648 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:53.648 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:29:53.648 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
ok 107 error should be null
,2016-03-24 15:29:53.651 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:53.651 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:29:53.651 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-24 15:30:43.176 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:43.176 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:30:43.176 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:30:43.177 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:43.178 ThaliTest[2096,:3652155] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51574
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-24 15:30:46.729 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:46.729 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:30:46.730 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:30:46.730 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:46.731 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51576
,2016-03-24 15:30:47.017 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements
,2016-03-24 15:30:47.018 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 15:30:47.029 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements: success
,2016-03-24 15:30:47.046 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 15:30:47.047 ThaliTest[2096:3652155] server: starting DD1A9DF3-8261-4279-BA77-CCA8E9F37311:3
,2016-03-24 15:30:47.048 ThaliTest[2096:3652155] THEMultipeerManager initialized peer DD1A9DF3-8261-4279-BA77-CCA8E9F37311:3
,2016-03-24 15:30:47.051 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-24 15:30:47.370 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
,2016-03-24 15:30:47.371 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
,2016-03-24 15:30:47.372 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
,2016-03-24 15:30:47.373 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
,2016-03-24 15:30:47.374 ThaliTest[2096:3652155] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:30:47.377 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 120 error should be null
,ok 121 error should be null
,# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
,ok 123 should not have been called more than once
,# teardown
,ok 124 error should be null
,ok 125 error should be null
,# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
,# teardown
,ok 127 error should be null
ok 128 error should be null
,# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
,ok 130 port should match
,ok 131 host address should be null
,ok 132 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 133 error should be null
,ok 134 error should be null
,# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 15:30:54.306 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements
2016-03-24 15:30:54.306 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 15:30:54.307 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-24 15:30:54.314 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
,2016-03-24 15:30:54.316 ThaliTest[2096:3652155] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:30:54.318 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-24 15:30:54.634 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:54.635 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 15:30:54.637 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:54.637 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:30:54.637 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: suc,cess
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 15:30:55.392 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements
2016-03-24 15:30:55.392 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:55.393 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 15:30:55.394 ThaliTest[2096:3652155] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:55.395 ThaliTest[2096:3652155] jxcore: startListeningForAdv,ertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 15:31:15.394 ThaliTest[2096:3652008] multipeer manager: restart client
,2016-03-24 15:31:32.890 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
2016-03-24 15:31:32.890 ThaliTest[2096:3652155] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
,2016-03-24 15:31:32.891 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 15:31:32.893 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:31:32.893 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:31:32.894 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 15:32:01.956 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:32:01.957 ThaliTest[2096:3652155] server: starting DD1A9DF3-8261-4279-BA77-CCA8E9F37311:4
2016-03-24 15:32:01.957 ThaliTest[2096:3652155] multipeer manager: start client restart timer: 0x176a7af0
2016-03-24 15:32:01.958 ThaliTest[2096:3652155] THEMultipeerManager initialized peer DD1A9DF3-8261-4279-BA77-CCA8E9F37311:4
2016-03-24 15:32:01.958 ThaliTest[2096:3652155] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 15:32:01.959 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:32:01.959 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016,-03-24 15:32:01.959 ThaliTest[2096:3652155] multipeer manager: stop client timer
2016-03-24 15:32:01.959 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 15:32:32.340 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:32:32.342 ThaliTest[2096:3652155] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 15:32:32.343 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening
2016-03-24 15:32:32.344 ThaliTest[2096:3652155] THEMultipeerManager stopping peer
2016-03-24 15:32:32.344 ThaliTest[2096:3652155] jxcore: stopAdvertisingAndListening: suc,cess
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup

```
