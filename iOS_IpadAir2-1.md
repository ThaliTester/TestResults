#### Test 67111490059a058_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/BF2EDD3F-AE02-4F59-A1C7-E9B82634C342/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BF2EDD3F-AE02-4F59-A1C7-E9B82634C342/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/67111490059a058/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54009"
,(lldb)     command script import "/tmp/BF2EDD3F-AE02-4F59-A1C7-E9B82634C342/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-20 04:47:25.595 ThaliTest[1024:2695611] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/45AAF9AD-8199-4250-AFB9-E3305FEA756D/Library/Cookies/Cookies.binarycookies
,2016-04-20 04:47:25.963 ThaliTest[1024:2695611] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-20 04:47:25.964 ThaliTest[1024:2695611] Multi-tasking -> Device: YES, App: YES
,2016-04-20 04:47:25.983 ThaliTest[1024:2695611] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-20 04:47:27.865 ThaliTest[1024:2695611] Using UIWebView
,2016-04-20 04:47:27.872 ThaliTest[1024:2695611] [CDVTimer][handleopenurl] 0.451982ms
,2016-04-20 04:47:27.880 ThaliTest[1024:2695611] [CDVTimer][intentandnavigationfilter] 7.337987ms
,2016-04-20 04:47:27.881 ThaliTest[1024:2695611] [CDVTimer][gesturehandler] 0.332952ms
,2016-04-20 04:47:27.881 ThaliTest[1024:2695611] [CDVTimer][TotalPluginStartup] 9.743989ms
,2016-04-20 04:47:34.608 ThaliTest[1024:2695611] Resetting plugins due to page load.
,2016-04-20 04:47:38.443 ThaliTest[1024:2695611] Finished load of: file:///var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/index.html
,2016-04-20 04:47:38.653 ThaliTest[1024:2695611] JXcore Cordova plugin initializing
,2016-04-20 04:47:38.655 ThaliTest[1024:2695871] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-20 04:47:45.276 ThaliTest[1024:2695871] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-20 04:47:45.277 ThaliTest[1024:2695871] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-04-20 04:47:45.277 ThaliTest[1024:2695871] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-20 04:47:45.278 ThaliTest[1024:2695871] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B11E7386-2124-4562-9A3A-6018683223BB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-20 04:47:51.137 ThaliTest[1024:2695611] THREAD WARNING: ['JXcore'] took '5576.004150' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53728
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53730
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
,DEBUG createNativeListener: listening 53733
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
,DEBUG createNativeListener: listening 53737
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
,DEBUG createNativeListener: listening 53742
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
,DEBUG createNativeListener: listening 53746
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53750
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
,DEBUG createNativeListener: listening 53754
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
,DEBUG createNativeListener: listening 53758
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
,DEBUG createNativeListener: listening 53810
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
,DEBUG createNativeListener: listening 53814
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
,# teardown
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
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
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
,[{"uuid":"bfdc7c82-3e48-4c76-97f8-19cc4d017af4","data":"custom data"},{"uuid":"193381e1-e38b-4d7e-b0af-8de5815cb621","data":"custom data"},{"uuid":"06642e6b-b55e-487b-9d1a-ac467e3aa68a","data":"custom data"},{"uuid":"da57b363-146c-4326-bcf1-87fd4d08657a",",data":"custom data"}]
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
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53824
,2016-04-20 04:50:08.696 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:08.697 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-20 04:50:08.699 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:08.700 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-20 04:50:08.781 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:08.782 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
2016-04-20 04:50:08.782 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,2016-04-20 04:50:08.782 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:08.783 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53826
,2016-04-20 04:50:08.985 ThaliTest[1024:2695871] jxcore: startListeningForAdvertisements
,2016-04-20 04:50:08.986 ThaliTest[1024:2695871] multipeer manager: start client restart timer: 0x175b90e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:08.988 ThaliTest[1024:2695871] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-20 04:50:09.012 ThaliTest[1024:2695871] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-20 04:50:09.014 ThaliTest[1024:2695871] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-20 04:50:09.318 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
,2016-04-20 04:50:09.318 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:09.319 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,2016-04-20 04:50:09.320 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
,2016-04-20 04:50:09.322 ThaliTest[1024:2695871] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:09.327 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53828
,2016-04-20 04:50:09.862 ThaliTest[1024:2695871] jxcore: startUpdateAdvertisingAndListening
,2016-04-20 04:50:09.862 ThaliTest[1024:2695871] server: starting A1C44B62-F329-4704-A7A7-5D86DB1D6308:1
,2016-04-20 04:50:09.863 ThaliTest[1024:2695871] multipeer manager: start client restart timer: 0x175b90e0
,2016-04-20 04:50:09.864 ThaliTest[1024:2695871] THEMultipeerManager initialized peer A1C44B62-F329-4704-A7A7-5D86DB1D6308:1
,2016-04-20 04:50:09.864 ThaliTest[1024:2695871] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-20 04:50:09.882 ThaliTest[1024:2695871] jxcore: startUpdateAdvertisingAndListening
2016-04-20 04:50:09.882 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:09.883 ThaliTest[1024:2695871] multipeer manager: stop client timer
,2016-04-20 04:50:09.884 ThaliTest[1024:2695871] server: starting A1C44B62-F329-4704-A7A7-5D86DB1D6308:2
,2016-04-20 04:50:09.887 ThaliTest[1024:2695871] multipeer manager: start client restart timer: 0x175b90e0
2016-04-20 04:50:09.887 ThaliTest[1024:2695871] THEMultipeerManager initialized peer A1C44B62-F329-4704-A7A7-5D86DB1D6308:2
2016-04-20 04:50:09.887 ThaliTest[1024:2695871] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-20 04:50:10.438 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
,2016-04-20 04:50:10.438 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:10.439 ThaliTest[1024:2695871] multipeer manager: stop client timer
2016-04-20 04:50:10.440 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,2016-04-20 04:50:10.444 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-20 04:50:10.446 ThaliTest[1024:26958,71] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53833
,2016-04-20 04:50:52.701 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
,2016-04-20 04:50:52.702 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:52.703 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-20 04:50:52.710 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
,2016-04-20 04:50:52.710 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:52.711 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-20 04:50:52.829 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
,2016-04-20 04:50:52.830 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:52.830 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,2016-04-20 04:50:52.832 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:52.834 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53835
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-20 04:50:53.146 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening
2016-04-20 04:50:53.147 ThaliTest[1024:2695871] THEMultipeerManager stopping peer
,2016-04-20 04:50:53.147 ThaliTest[1024:2695871] jxcore: stopAdvertisingAndListening: success
,2016-04-20 04:50:53.148 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-20 04:50:53.150 ThaliTest[1024:2695871] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53837
,2016-04-20 04:50:53.361 ThaliTest[1024:2695871] jxcore: startListeningForAdvertisements
,2016-04-20 04:50:53.363 ThaliTest[1024:2695871] multipeer manager: start client restart timer: 0x175b90e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-20 04:50:53.368 ThaliTest[1024:2695871] jxcore: startListeningForAdvertisements: success
,2016-04-20 04:50:53.391 ThaliTest[1024:2695871] jxcore: startUpdateAdvertisingAndListening
,2016-04-20 04:50:53.391 ThaliTest[1024:2695871] server: starting A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
,2016-04-20 04:50:53.392 ThaliTest[1024:2695871] THEMultipeerManager initialized peer A1C44B62-F329-4704-A7A7-5D86DB1D6308:3
2016-04-20 04:50:53.393 ThaliTest[1024:2695871] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-20 04:50:54.080 ThaliTest[1024:2695611] client: found new peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:2
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:50:54.405 ThaliTest[1024:2695611] client: found new peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:2
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:50:54.523 ThaliTest[1024:2695611] client: found new peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:50:54.672 ThaliTest[1024:2695611] client: found new peer: 33B8A67F-CB3A-4E1D-BE92-04CE29FBE967:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:51:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:51:13.382 ThaliTest[1024:2695611] client: found updated peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:51:13.383 ThaliTest[1024:2695611] client: found updated peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:51:13.390 ThaliTest[1024:2695611] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,DEBUG createPeerListener: createPeerListener creating new server
,DEBUG createPeerListener: pleaseConnect= 0
,2016-04-20 04:51:33.364 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:51:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:51:33.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:51:33.390 ThaliTest[1024:2695611] client: found existing peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E:3
,2016-04-20 04:51:47.638 ThaliTest[1024:2695611] client: lost peer: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E
2016-04-20 04:51:47.639 ThaliTest[1024:2695611] client session: onPeerLost: CC6E7DBB-99E2-4030-ABCE-2D3165456B3E
,2016-04-20 04:51:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:51:53.382 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:51:53.383 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:52:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:52:13.385 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:52:13.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:52:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:52:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:52:33.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:52:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:52:53.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:52:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:53:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:53:13.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:53:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:53:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:53:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:53:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:53:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:53:53.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:53:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:54:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:54:13.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:54:13.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:54:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:54:33.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:54:33.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:54:53.364 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:54:53.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:54:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:55:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:55:13.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:55:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:55:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:55:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:55:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:55:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:55:53.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:55:53.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:56:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:56:13.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:56:13.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:56:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:56:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:56:33.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:56:53.364 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:56:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:56:53.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:57:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:57:13.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:57:13.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:57:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:57:33.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:57:33.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:57:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:57:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:57:53.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:58:13.363 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:58:13.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:58:13.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:58:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:58:33.389 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:58:33.389 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:58:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:58:53.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 04:58:53.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 04:59:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:59:13.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:59:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:59:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:59:33.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:59:33.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 04:59:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 04:59:53.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 04:59:53.385 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:00:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:00:13.385 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:00:13.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:00:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:00:33.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:00:33.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:00:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:00:53.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:00:53.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:01:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:01:13.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:01:13.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:01:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:01:33.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:01:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:01:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:01:53.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:01:53.389 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:02:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:02:13.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:02:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:02:33.364 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:02:33.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:02:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:02:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:02:53.384 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:02:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:03:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:03:13.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:03:13.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:03:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:03:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:03:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:03:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:03:53.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:03:53.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:04:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:04:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:04:13.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:04:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:04:33.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:04:33.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:04:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:04:53.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:04:53.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:05:13.364 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:05:13.385 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:05:13.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:05:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:05:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:05:33.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:05:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:05:53.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:05:53.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:06:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:06:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:06:13.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:06:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:06:33.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:06:33.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:06:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:06:53.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:06:53.387 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:07:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:07:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:07:13.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:07:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:07:33.388 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:07:33.388 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:07:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:07:53.384 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:07:53.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:08:13.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:08:13.385 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
2016-04-20 05:08:13.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,2016-04-20 05:08:33.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:08:33.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:08:33.387 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3
,2016-04-20 05:08:53.365 ThaliTest[1024:2695611] multipeer manager: restart client
,2016-04-20 05:08:53.386 ThaliTest[1024:2695611] client: found existing peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
2016-04-20 05:08:53.386 ThaliTest[1024:2695611] client: found existing peer: DF7D62F5-96D1-401F-B736-926B7A8C54F1:3

```
