#### Test 64746945aaa3c62_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/D6790500-0C85-462B-8CE5-91787A2DAD65/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D6790500-0C85-462B-8CE5-91787A2DAD65/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64746945aaa3c62/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49629"
,(lldb)     command script import "/tmp/D6790500-0C85-462B-8CE5-91787A2DAD65/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-31 10:09:51.126 ThaliTest[1920:4912716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/050A9A97-FE95-4B0C-9FA1-2738B605703F/Library/Cookies/Cookies.binarycookies
,2016-03-31 10:09:51.228 ThaliTest[1920:4912716] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-31 10:09:51.230 ThaliTest[1920:4912716] Multi-tasking -> Device: YES, App: YES
,2016-03-31 10:09:51.247 ThaliTest[1920:4912716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-31 10:09:52.404 ThaliTest[1920:4912716] Using UIWebView
2016-03-31 10:09:52.408 ThaliTest[1920:4912716] [CDVTimer][handleopenurl] 0.308037ms
,2016-03-31 10:09:52.414 ThaliTest[1920:4912716] [CDVTimer][intentandnavigationfilter] 5.636990ms
2016-03-31 10:09:52.414 ThaliTest[1920:4912716] [CDVTimer][gesturehandler] 0.238001ms
2016-03-31 10:09:52.414 ThaliTest[1920:4912716] [CDVTimer][TotalPluginStartup] 7.081985ms
,2016-03-31 10:09:57.303 ThaliTest[1920:4912716] Resetting plugins due to page load.
,2016-03-31 10:09:59.466 ThaliTest[1920:4912716] Finished load of: file:///var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/index.html
,2016-03-31 10:09:59.655 ThaliTest[1920:4912716] JXcore Cordova plugin initializing
,2016-03-31 10:09:59.781 ThaliTest[1920:4912865] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-31 10:10:13.892 ThaliTest[1920:4912865] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:10:13.892 ThaliTest[1920:4912865] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:10:13.892 ThaliTest[1920:4,912865] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 10:10:13.896 ThaliTest[1920:4912865] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA40DF40-E294-4394-BCA6-4C818EBC00F3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55855
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55857
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
,DEBUG createNativeListener: listening 55860
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55864
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55869
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
DEBUG createNativeListener: listening 55873
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
DEBUG createNativeListener: listening 55877
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
DEBUG createNativeListener: listening 55881
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 55885
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListene,r: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 55937
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
,DEBUG createNativeListener: listening 55941
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
ok 43 The mux object should be c,losed
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
,# 16. multiplex can send data
,ok 48 String should be length:200
,# teardown
,# setup
,# 17. enqueue and run in order
,ok 49 firstPromise setTimeout
ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
,ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
ok 59 thirdPromise - in resolve
,ok 60 secondPromise - second to run
,ok 61 secondPromise - in catch
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
,ok 71 third
,ok 72 thirdPromise - in then
,ok 73 testingPromises
,# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
# teardown
,# setup
,# 22. another
,ok 76 sane
,# teardown
,# setup
,# 23. can pass data in setup
,ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
,ok 83 own UUID is found from the participants list
,# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 84 specific error should be returned
# teardown
,ok 85 error should be null
ok 86 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 87 specific error should be returned
# teardown
,ok 88 error should be null
ok 89 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55953
2016-03-31 10:13:05.502 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.503 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
,ok 91 error should be null
,2016-03-31 10:13:05.509 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.510 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
# teardown
,2016-03-31 10:13:05.633 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:05.633 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:05.633 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:05.634 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:05.635 ThaliTest[1920,:4912865] jxcore: stopListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55955
2016-03-31 10:13:06.021 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
,2016-03-31 10:13:06.023 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:06.024 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
ok 97 error should be null
2016-03-31 10:13:06.036 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:06.037 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 98 error should be null
ok 99 error should be null
# teardown
,2016-03-31 10:13:06.822 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:06.822 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:06.822 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:06.823 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:06.824 ThaliTest[1920:4912865] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:06.825 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 100 error should be null
ok 101 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55957
,2016-03-31 10:13:07.365 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:07.365 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:1
2016-03-31 10:13:07.366 ThaliTest[1920:4912865] multipeer m,anager: start client restart timer: 0x1758f330
2016-03-31 10:13:07.366 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:1
2016-03-31 10:13:07.366 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
2016-03-31 10:13:07.380 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:07.380 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:07.380, ThaliTest[1920:4912865] multipeer manager: stop client timer
2016-03-31 10:13:07.381 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:2
,2016-03-31 10:13:07.381 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
,2016-03-31 10:13:07.391 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:2
,2016-03-31 10:13:07.397 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening: success
,ok 104 error should be null
,ok 105 error should be null
,# teardown
,2016-03-31 10:13:08.018 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.018 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:08.018 ThaliTest[1920:4912865] multipeer manager: stop client timer
20,16-03-31 10:13:08.018 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
2016-03-31 10:13:08.019 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:08.020 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 106 error should be null
,ok 107 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55962
,2016-03-31 10:13:08.531 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.531 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:08.531 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: suc,cess
ok 108 error should be null
ok 109 error should be null
2016-03-31 10:13:08.534 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:08.535 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:08.535 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
,ok 110 error should be null
,ok 111 error should be null
,# teardown
,2016-03-31 10:13:08.629 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
,2016-03-31 10:13:08.629 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
,2016-03-31 10:13:08.630 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
,2016-03-31 10:13:08.631 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 10:13:08.633 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,ok 112 error should be null
,ok 113 error should be null
,# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55964
ok 114 first call should succeed
ok 115 first call should succeed
ok 116 specific error should be returned
# teardown
,2016-03-31 10:13:09.513 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:09.513 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:09.514 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:09.514 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:09.515 ThaliTest[1920,:4912865] jxcore: stopListeningForAdvertisements: success
ok 117 error should be null
ok 118 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55966
2016-03-31 10:13:09.918 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
,2016-03-31 10:13:09.918 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:09.920 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
,2016-03-31 10:13:09.952 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:13:09.952 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:3
2016-03-31 10:13:09.953 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:3
2016-03-31 10:13:09.953 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening: success
,ok 119 called only once
ok 120 discovery state matches
ok 121 advertising state matches
,# teardown
,2016-03-31 10:13:10.100 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:10.100 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:13:10.101 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:13:10.101 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:10.101 ThaliTest[1920:4912865] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:10.102 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 122 error should be null
ok 123 error should be null
# setup
,# 32. does not send duplicate availability changes
,ok 124 should be called once
ok 125 should not have been called more than once
# teardown
,ok 126 error should be null
,ok 127 error should be null
,# setup
,# 33. can get the network status
,ok 128 network status should have certain non-empty properties
,# teardown
,ok 129 error should be null
ok 130 error should be null
# setup
,# 34. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 131 host address should match
ok 132 port should match
,ok 133 host address should be null
,ok 134 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 135 error should be null
ok 136 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-31 10:13:41.285 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
2016-03-31 10:13:41.286 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:13:41.287 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-31 10:13:41.288 ThaliTes,t[1920:4912865] jxcore: stopListeningForAdvertisements
2016-03-31 10:13:41.288 ThaliTest[1920:4912865] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-31 10:13:41.289 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
ok 138 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-31 10:13:45.391 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:13:45.392 ThaliTest[1920:49128,65] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:13:45.393 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:13:45.394 ThaliTest[1920:491286,5] THEMultipeerManager stopping peer
2016-03-31 10:13:45.394 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-31 10:14:08.910 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
2016-03-31 10:14:08.910 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:14:08.911 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements without error
2016-03-31 10:14:08.912 ThaliTes,t[1920:4912865] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:14:08.913 ThaliTest[1920:4912865] jxcore: startListeningForAdv,ertisements: success
ok 142 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-31 10:14:20.075 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
2016-03-31 10:14:20.075 ThaliTest[1920:4912865] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-31 10:14:20.076 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:14:20.078 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:20.078 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:1,4:20.078 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-03-31 10:14:30.547 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:14:30.547 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:4
2016-03-31 10:14:30.548 ThaliTest[1920:4912865] multipeer m,anager: start client restart timer: 0x1758f330
2016-03-31 10:14:30.548 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:4
2016-03-31 10:14:30.548 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:14:30.549 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:30.550 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
,2016-03-31 10:14:30.550 ThaliTest[1920:4912865] multipeer manager: stop client timer
2016-03-31 10:14:30.555 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 146 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-31 10:14:52.149 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:14:52.150 ThaliTest[1920:49128,65] jxcore: stopListeningForAdvertisements: success
ok 147 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:14:52.151 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:14:52.151 ThaliTest[1920:491286,5] THEMultipeerManager stopping peer
2016-03-31 10:14:52.151 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-31 10:16:15.304 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:15.305 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:5
2016-03-31 10:16:15.305 ThaliTest[1920:4912865] multipeer m,anager: start client restart timer: 0x1758f330
2016-03-31 10:16:15.305 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:5
2016-03-31 10:16:15.305 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 149 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:16:15.307 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:15.307 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
,2016-03-31 10:16:15.307 ThaliTest[1920:4912865] multipeer manager: stop client timer
2016-03-31 10:16:15.313 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:6
2016-03-31 10:16:15.314 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
2016-03-31 10:16:15.314 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:6
2016-03-31 10:16:15.314 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListenin,g: success
ok 150 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-31 10:16:15.792 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:16:15.793 ThaliTest[1920:491286,5] jxcore: stopListeningForAdvertisements: success
ok 151 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:16:15.794 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:16:15.794 ThaliTest[1920:4912865,] THEMultipeerManager stopping peer
2016-03-31 10:16:15.794 ThaliTest[1920:4912865] multipeer manager: stop client timer
2016-03-31 10:16:15.794 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdver,tisingAndListening in teardown
# setup
,# 39. peerAvailabilityChange is called
,2016-03-31 10:16:16.315 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:16.315 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:16.315 ThaliTest[1920:4912865] multipeer m,anager: start client restart timer: 0x1758f330
2016-03-31 10:16:16.315 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7
2016-03-31 10:16:16.316 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 153 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-31 10:16:16.317 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-31 10:16:16.318 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-31 10:16:17.642 ThaliTest[1920:4912716] client: found new peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:7
ok 155 peers must be an array
ok 156 peers must not be zero-length
,ok 157 peer must have peerIdentifier
ok 158 peerIdentifier must be a string
ok 159 peer must have peerAvailable
,ok 160 peer must have pleaseConnect
,# teardown
,2016-03-31 10:16:18.101 ThaliTest[1920:4912716] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
,2016-03-31 10:16:18.229 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-31 10:16:18.231 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,ok 161 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-31 10:16:18.232 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:16:18.233 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:16:18.233 ThaliTest[1920:4912865] multipeer manager: stop client timer
20,16-03-31 10:16:18.233 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. Can connect to a remote peer
,2016-03-31 10:16:18.761 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:16:18.761 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:18.762 ThaliTest[1920:4912865] multipeer m,anager: start client restart timer: 0x1758f330
2016-03-31 10:16:18.762 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8
2016-03-31 10:16:18.762 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 163 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:16:18.764 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 10:16:18.765 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 164 Can call startListeningForAdvertisements without error
,2016-03-31 10:16:19.668 ThaliTest[1920:4912716] client: found new peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2F92EB85-432C-485C-AE1C-D018859FD29C:7","pleaseConnect":0}]
2016-03-31 10:16:19.670 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:19.670 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:19.671 ThaliTest[1920:4912865] cli,ent session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:20.921 ThaliTest[1920:4912716] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3F6A8788-1777-4148-9D5D-A7C8608DD267:7","pleaseConnect":0}]
,2016-03-31 10:16:21.069 ThaliTest[1920:4913640] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:21.069 ThaliTest[1920:4913640] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:21.0,69 ThaliTest[1920:4913640] client session: disconnect
2016-03-31 10:16:21.069 ThaliTest[1920:4913640] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:21.071 ThaliTest[1920:4913640] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:21.071 ThaliTest[1920:4913640] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-31 10:16:21.303 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:16:21.304 ThaliTest[1920:4912716] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC,2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:16:24.075 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:24.076 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:24.076 ThaliTest[1920:4912865] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:24.337 ThaliTest[1920:4913640] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:24.339 ThaliTest[1920:4913640] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:24.3,39 ThaliTest[1920:4913640] client session: disconnect
2016-03-31 10:16:24.340 ThaliTest[1920:4913640] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:24.340 ThaliTest[1920:4913640] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:24.340 ThaliTest[1920:4913640] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-31 10:16:27.354 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:27.354 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:27.354 ThaliTest[1920:4912865] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:27.524 ThaliTest[1920:4913640] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:27.525 ThaliTest[1920:4913640] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:27.5,26 ThaliTest[1920:4913640] client session: disconnect
2016-03-31 10:16:27.526 ThaliTest[1920:4913640] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:27.526 ThaliTest[1920:4913640] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:27.526 ThaliTest[1920:4913640] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-31 10:16:30.533 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:30.534 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:30.534 ThaliTest[1920:4912865] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:30.667 ThaliTest[1920:4913640] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:30.667 ThaliTest[1920:4913640] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:30.668 ThaliTest[1920:4913640] client session: disconnect
,2016-03-31 10:16:30.668 ThaliTest[1920:4913640] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:30.670 ThaliTest[1920:4913640] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
,2016-03-31 10:16:30.670 ThaliTest[1920:4913640] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-31 10:16:32.799 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:16:32.799 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:16:32.799 ThaliTest[1920:4912716], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:16:33.682 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:33.682 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:33.682 ThaliTest[1920:4912865] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:33.817 ThaliTest[1920:4913692] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:33.817 ThaliTest[1920:4913692] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:33.819 ThaliTest[1920:4913692] client session: disconnect
2016-03-31 10:16:33.819 ThaliTest[1920:4913692] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:33.821 ThaliTest[1920:4913692] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:33.821 ThaliTest[1920:4913692] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-31 10:16:36.835 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:36.835 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:36.836 ThaliTest[1920:4912865] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:7
,2016-03-31 10:16:36.964 ThaliTest[1920:4913692] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:36.964 ThaliTest[1920:4913692] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:36.9,64 ThaliTest[1920:4913692] client session: disconnect
2016-03-31 10:16:36.965 ThaliTest[1920:4913692] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:36.965 ThaliTest[1920:4913692] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:36.967 ThaliTest[1920:4913692] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-03-31 10:16:38.763 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:16:38.791 ThaliTest[1920:4912716] client: found updated peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:38.792 ThaliTest[1920:4912716] client: found updated peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
INFO testThaliMobileNati,ve: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2F92EB85-432C-485C-AE1C-D018859FD29C:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier,":"3F6A8788-1777-4148-9D5D-A7C8608DD267:8","pleaseConnect":0}]
,2016-03-31 10:16:39.975 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:39.976 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:39.976 ThaliTest[1920:4912865] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:40.082 ThaliTest[1920:4913692] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:40.083 ThaliTest[1920:4913692] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:40.0,83 ThaliTest[1920:4913692] client session: disconnect
2016-03-31 10:16:40.083 ThaliTest[1920:4913692] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:40.084 ThaliTest[1920:4913692] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:40.084 ThaliTest[1920:4913692] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-31 10:16:43.096 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:43.096 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:43.096 ThaliTest[1920:4912865] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:43.319 ThaliTest[1920:4913644] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:43.320 ThaliTest[1920:4913644] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:43.3,20 ThaliTest[1920:4913644] client session: disconnect
2016-03-31 10:16:43.320 ThaliTest[1920:4913644] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:43.321 ThaliTest[1920:4913644] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:43.321 ThaliTest[1920:4913644] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-31 10:16:45.872 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:16:45.873 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:16:45.873 ThaliTest[1920:4912716] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:16:46.335 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:46.336 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:46.336 ThaliTest[1920:4912865] client session: stateChange:0->,1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:46.494 ThaliTest[1920:4913641] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:46.494 ThaliTest[1920:4913641] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:46.494 ThaliTest[1920:4913641] client session: disconnect
,2016-03-31 10:16:46.494 ThaliTest[1920:4913641] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:46.496 ThaliTest[1920:4913641] client session: fireConnectCallback: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 1,0:16:46.497 ThaliTest[1920:4913641] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-31 10:16:49.508 ThaliTest[1920:4912865] jxcore: connect 2F92EB85-432C-485C-AE1C-D018859FD29C:7
2016-03-31 10:16:49.508 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:16:49.508 ThaliTest[1920:4912865] client session: stateChange:0->1 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:49.618 ThaliTest[1920:4913692] client session: not connected 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:49.620 ThaliTest[1920:4913692] client session: onLinkFailure: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:49.6,20 ThaliTest[1920:4913692] client session: disconnect
2016-03-31 10:16:49.620 ThaliTest[1920:4913692] client session: stateChange:1->0 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:16:49.621 ThaliTest[1920:4913692] client session: fireConnectCallb,ack: 2F92EB85-432C-485C-AE1C-D018859FD29C
2016-03-31 10:16:49.621 ThaliTest[1920:4913692] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 165 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-31 10:16:58.763 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:16:58.784 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:16:58.794 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:16:59.037 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:16:59.038 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:16:59.038 ThaliTest[1920:4912716], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:17:12.060 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:17:12.060 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:17:12.060 ThaliTest[1920:4912716], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:17:18.762 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:17:18.780 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:17:18.781 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:17:25.183 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:17:25.184 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:17:25.184 ThaliTest[1920:4912716], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:17:37.843 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:17:37.844 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:17:37.845 ThaliTest[1920:4912716] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:17:38.762 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:17:38.784 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
,2016-03-31 10:17:38.793 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:17:51.264 ThaliTest[1920:4912716] client: lost peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:17:51.264 ThaliTest[1920:4912716] client session: onPeerLost: 3F6A8788-1777-4148-9D5D-A7C8608DD267
,2016-03-31 10:17:51.866 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:17:51.867 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:17:51.867 ThaliTest[1920:4912716] server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:17:58.763 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:17:58.783 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:8
2016-03-31 10:17:58.784 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
INFO testThaliMobileNa,tive: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"3F6A8788-1777-4148-9D5D-A7C8608DD267:8","pleaseConnect":0}]
,2016-03-31 10:18:03.973 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:18:03.973 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:18:03.973 ThaliTest[1920:4912716], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:18:17.080 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:18:17.080 ThaliTest[1920:4912716] server: disconnecting to refresh session (2F92EB85-432C-485C-AE1C-D018859FD29C)
2016-03-31 10:18:17.081 ThaliTest[1920:4912716], server: rejecting invitation from 2F92EB85-432C-485C-AE1C-D018859FD29C due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:7)
,2016-03-31 10:18:18.763 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:18:18.786 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:8
,2016-03-31 10:18:27.972 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:18:27.973 ThaliTest[1920:491286,5] jxcore: stopListeningForAdvertisements: success
ok 166 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:18:27.975 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:18:27.975 ThaliTest[1920:4912865,] THEMultipeerManager stopping peer
2016-03-31 10:18:27.975 ThaliTest[1920:4912865] multipeer manager: stop client timer
2016-03-31 10:18:27.976 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 167 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. Can shift large amounts of data
,2016-03-31 10:18:31.819 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndListening
2016-03-31 10:18:31.820 ThaliTest[1920:4912865] server: starting 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
2016-03-31 10:18:31.820 ThaliTest[1920:4912865] multipeer m,anager: start client restart timer: 0x1758f330
2016-03-31 10:18:31.820 ThaliTest[1920:4912865] THEMultipeerManager initialized peer 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9
2016-03-31 10:18:31.820 ThaliTest[1920:4912865] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 168 Can call startUpdateAdvertisingAndListening without error
2016-03-31 10:18:31.822 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-31 10:18:31.823 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
,ok 169 Can call startListeningForAdvertisements without error
,2016-03-31 10:18:33.735 ThaliTest[1920:4912716] client: found new peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:18:33.735 ThaliTest[1920:4912716] client: found new peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:18:33.737 ThaliTes,t[1920:4912865] jxcore: connect 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:18:33.737 ThaliTest[1920:4912865] client session: connect
2016-03-31 10:18:33.737 ThaliTest[1920:4912865] client session: stateChange:0->1 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:18:33.794 ThaliTest[1920:4912716] multipeer session: reset timer
2016-03-31 10:18:33.794 ThaliTest[1920:4912716] server: rejecting invitation from 3F6A8788-1777-4148-9D5D-A7C8608DD267 due to previous generation (87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:9 != 87D010AC-7D98-4E04-91FC-9CBBC2D2DD5C:8)
,2016-03-31 10:18:36.355 ThaliTest[1920:4914071] client session: p2p link connected
,2016-03-31 10:18:36.362 ThaliTest[1920:4914071] client session: stateChange:1->2 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:18:36.362 ThaliTest[1920:4914071] client session: fireConnectCallback: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:18:36.362 ThaliTest[1920:4914071] jxcore: connect: success
INFO testThaliMobileNative: 
,INFO testThaliMobileNative: Forward connection
,2016-03-31 10:18:36.367 ThaliTest[1920:4912716] client: relay established
,2016-03-31 10:18:36.367 ThaliTest[1920:4912716] client: new accepted socket: 0x1ded5b60
,INFO testThaliMobileNative: forwardSend
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,ok 170 received should match sent forward
,# teardown
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:18:51.821 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:18:51.843 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:18:51.843 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:19:11.821 ThaliTest[1920:4912716] multipeer manager: restart client
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:19:11.854 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:19:11.855 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:19:31.821 ThaliTest[1920:4912716] multipeer manager: restart client
,INFO testThaliMobileNative: forwardData
2016-03-31 10:19:31.854 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:19:31.858 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:19:51.821 ThaliTest[1920:4912716] multipeer manager: restart client
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:19:51.860 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:19:51.862 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:20:11.821 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:20:11.851 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
,2016-03-31 10:20:11.854 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:20:31.821 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:20:31.850 ThaliTest[1920:4912716] client: found existing peer: 2F92EB85-432C-485C-AE1C-D018859FD29C:9
2016-03-31 10:20:31.850 ThaliTest[1920:4912716] client: found existing peer: 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,INFO testThaliMobileNative: forwardData
,2016-03-31 10:20:41.062 ThaliTest[1920:4914116] client session: not connected 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
2016-03-31 10:20:41.062 ThaliTest[1920:4914116] client session: onLinkFailure: 3F6A8788-1777-4148-9D5D-A7C8608DD267
2016-03-31 10:20:41.0,62 ThaliTest[1920:4914116] client session: disconnect
2016-03-31 10:20:41.062 ThaliTest[1920:4914116] client session: stateChange:2->0 3F6A8788-1777-4148-9D5D-A7C8608DD267:9
,2016-03-31 10:20:41.108 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-31 10:20:41.109 ThaliTest[1920:491286,5] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
2016-03-31 10:20:41.110 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:20:41.110 ThaliTest[1920:4912865,] THEMultipeerManager stopping peer
2016-03-31 10:20:41.110 ThaliTest[1920:4912865] multipeer manager: stop client timer
2016-03-31 10:20:41.111 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# setup
,2016-03-31 10:20:42.088 ThaliTest[1920:4912865] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:42.089 ThaliTest[1920:4912865] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:42.089 ThaliTest[1920:4,912865] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 10:20:42.091 ThaliTest[1920:4912865] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
# 42. #startListeningForAdvertisements should fail if start not called
,ok 173 specific error should be returned
# teardown
,ok 174 must be stopped
# setup
,2016-03-31 10:20:44.813 ThaliTest[1920:4912865] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:44.814 ThaliTest[1920:4912865] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:44.814 ThaliTest[1920:4,912865] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:44.815 ThaliTest[1920:4912865] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. #startUpdateAdvertisingAndListening should fail if start not called
,ok 175 specific error should be returned
,# teardown
,ok 176 must be stopped
# setup
,2016-03-31 10:20:45.786 ThaliTest[1920:4912865] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:45.786 ThaliTest[1920:4912865] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:45.786 ThaliTest[1920:4912865] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-31 10:20:45.788 ThaliTest[1920:4912865] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
# 44. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55992
,2016-03-31 10:20:47.806 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:47.807 ThaliTest[1920:49128,65] jxcore: stopListeningForAdvertisements: success
ok 177 no errors
2016-03-31 10:20:47.809 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,,"discoveryActive":false}
2016-03-31 10:20:47.809 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
ok 178 still no errors
# teardown
,2016-03-31 10:20:48.180 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening
2016-03-31 10:20:48.180 ThaliTest[1920:4912865] THEMultipeerManager stopping peer
2016-03-31 10:20:48.180 ThaliTest[1920:4912865] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-31 10:20:48.181 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-31 10:20:48.182 ThaliTest[1920:4912865] jxcore: stopListeningForAdvertisements: success
,ok 179 must be stopped
,# setup
,2016-03-31 10:20:48.331 ThaliTest[1920:4912865] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-31 10:20:48.332 ThaliTest[1920:4912865] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-31 10:20:48.332 ThaliTest[1920:4,912865] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-31 10:20:48.333 ThaliTest[1920:4912865] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 55994
,2016-03-31 10:20:48.978 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements
2016-03-31 10:20:48.978 ThaliTest[1920:4912865] multipeer manager: start client restart timer: 0x1758f330
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:20:48.979 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 180 no errors
2016-03-31 10:20:48.981 ThaliTest[1920:4912865] jxcore: startListeningForAdve,rtisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-31 10:20:48.981 ThaliTest[1920:4912865] jxcore: startListeningForAdvertisements: success
ok 181 still no errors
# teardown
,2016-03-31 10:21:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:21:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:21:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:22:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:22:28.979 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:22:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:23:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:23:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:23:48.979 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:24:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:24:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:24:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:25:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:25:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:25:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:26:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:26:28.979 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:26:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:27:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:27:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:27:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:28:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:28:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:28:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:29:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:29:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:29:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:30:08.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:30:28.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:30:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:31:08.979 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:31:28.979 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:31:48.980 ThaliTest[1920:4912716] multipeer manager: restart client
,2016-03-31 10:32:08.980 ThaliTest[1920:4912716] multipeer manager: restart client

```
