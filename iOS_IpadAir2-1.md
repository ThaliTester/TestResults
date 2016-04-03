#### Test 64809936d936b9e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/AFF8E71F-C000-4378-96EA-BD058E488B71/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AFF8E71F-C000-4378-96EA-BD058E488B71/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64809936d936b9e/build_ios/ThaliTest.app' (armv7).
,(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50522"
,(lldb)     command script import "/tmp/AFF8E71F-C000-4378-96EA-BD058E488B71/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-03 21:07:22.679 ThaliTest[404:406254] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9A1F91C0-9A58-43DF-A8A6-EAF9A5450CA2/Library/Cookies/Cookies.binarycookies
,2016-04-03 21:07:23.095 ThaliTest[404:406254] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-03 21:07:23.096 ThaliTest[404:406254] Multi-tasking -> Device: YES, App: YES
,2016-04-03 21:07:23.114 ThaliTest[404:406254] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-03 21:07:25.427 ThaliTest[404:406254] Using UIWebView
,2016-04-03 21:07:25.433 ThaliTest[404:406254] [CDVTimer][handleopenurl] 0.442982ms
,2016-04-03 21:07:25.441 ThaliTest[404:406254] [CDVTimer][intentandnavigationfilter] 6.563962ms
,2016-04-03 21:07:25.441 ThaliTest[404:406254] [CDVTimer][gesturehandler] 0.306964ms
,2016-04-03 21:07:25.442 ThaliTest[404:406254] [CDVTimer][TotalPluginStartup] 8.885980ms
,2016-04-03 21:07:33.223 ThaliTest[404:406254] Resetting plugins due to page load.
,2016-04-03 21:07:37.382 ThaliTest[404:406254] Finished load of: file:///var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/index.html
,2016-04-03 21:07:37.588 ThaliTest[404:406254] JXcore Cordova plugin initializing
,2016-04-03 21:07:37.589 ThaliTest[404:406685] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-03 21:07:44.106 ThaliTest[404:406685] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-04-03 21:07:44.106 ThaliTest[404:406685] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-03 21:07:44.106 ThaliTest[404:406685] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-03 21:07:44.108 ThaliTest[404:406685] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9DCF01E1-37E1-46BA-9C22-841F868CCCD4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-03 21:07:49.381 ThaliTest[404:406254] THREAD WARNING: ['JXcore'] took '4995.479980' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50930
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50932
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
,DEBUG createNativeListener: listening 50935
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
,DEBUG createNativeListener: listening 50939
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
,DEBUG createNativeListener: listening 50944
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
,DEBUG createNativeListener: listening 50948
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
,DEBUG createNativeListener: listening 50952
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
,DEBUG createNativeListener: listening 50956
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
,DEBUG createNativeListener: listening 50960
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
,DEBUG createNativeListener: listening 51012
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
,DEBUG createNativeListener: listening 51016
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
,ok 69 firstPromise - in catch
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
,[{"uuid":"f6d73446-5000-4d78-b1ff-7f7cf59b2a18","data":"custom data"},{"uuid":"09cac296-ea8d-47c3-aafb-b2ba98d948de","data":"custom data"},{"uuid":"7f465dac-b5fc-4fa0-aece-e506c38feb66","data":"custom data"},{"uuid":"24de18a5-460b-493f-8720-a0ac5fddea1c","data":"custom data"}]
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
,DEBUG createNativeListener: listening 51026
,2016-04-03 21:10:43.732 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:43.734 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-03 21:10:43.738 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:43.739 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-03 21:10:43.881 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:10:43.882 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:43.883 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:43.884 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:43.886 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51028
,2016-04-03 21:10:44.174 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
,2016-04-03 21:10:44.175 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:10:44.177 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-03 21:10:44.204 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:10:44.206 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-03 21:10:44.627 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:44.628 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:44.628 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:44.630 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,2016-04-03 21:10:44.630 ThaliTest[404:406685] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:44.632 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51030
,2016-04-03 21:10:45.203 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:10:45.204 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:1
,2016-04-03 21:10:45.205 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,2016-04-03 21:10:45.206 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:1
,2016-04-03 21:10:45.207 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-03 21:10:45.236 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:10:45.237 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:45.237 ThaliTest[404:406685] multipeer manager: stop client timer
2016-04-03 21:10:45.238 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:2
,2016-04-03 21:10:45.240 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
2016-04-03 21:10:45.241 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:2
2016-04-03 21:10:45.241 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-03 21:10:45.646 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:45.647 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:45.647 ThaliTest[404:406685] multipeer manager: stop client timer
,2016-04-03 21:10:45.649 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:45.652 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:45.654 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51035
,2016-04-03 21:10:46.116 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:10:46.116 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:46.116 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-03 21:10:46.123 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:10:46.124 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:46.124 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-03 21:10:46.232 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
2016-04-03 21:10:46.232 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:46.233 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:46.234 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:46.237 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51037
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-03 21:10:47.138 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:10:47.138 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:10:47.139 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:47.140 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:47.143 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51039
,2016-04-03 21:10:48.133 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
,2016-04-03 21:10:48.134 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:10:48.137 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
,2016-04-03 21:10:48.160 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:10:48.161 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:3
,2016-04-03 21:10:48.162 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:3
2016-04-03 21:10:48.162 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-03 21:10:48.565 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:10:48.566 ThaliTest[404:406685] THEMultipeerManager stopping peer
2016-04-03 21:10:48.566 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,2016-04-03 21:10:48.568 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
2016-04-03 21:10:48.569 ThaliTest[404:406685] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:10:48.572 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
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
,ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
,# teardown
,ok 130 error should be null
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-03 21:11:50.209 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
,2016-04-03 21:11:50.210 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-03 21:11:50.216 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
,2016-04-03 21:11:50.219 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
2016-04-03 21:11:50.220 ThaliTest[404:406685] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:11:50.224 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-03 21:11:50.526 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:11:50.529 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:11:50.531 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:11:50.532 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:11:50.533 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-03 21:11:50.985 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
,2016-04-03 21:11:50.986 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:11:50.989 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
,2016-04-03 21:11:50.992 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-03 21:11:50.994 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-03 21:11:51.100 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,2016-04-03 21:11:51.101 ThaliTest[404:406685] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:11:51.104 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:11:51.106 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
2016-04-03 21:11:51.107 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:11:51.107 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-03 21:12:19.258 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:12:19.260 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-03 21:12:19.263 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:12:19.265 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-03 21:12:21.107 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:12:21.109 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:12:21.111 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:12:21.112 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:12:21.113 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-03 21:12:21.365 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:12:21.366 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:4
,2016-04-03 21:12:21.367 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
2016-04-03 21:12:21.368 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:4
,2016-04-03 21:12:21.368 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-03 21:12:21.371 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:12:21.371 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:12:21.372 ThaliTest[404:406685] multipeer manager: stop client timer
2016-04-03 21:12:21.372 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-03 21:12:21.690 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:12:21.693 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:12:21.696 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:12:21.696 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:12:21.697 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-03 21:13:48.276 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:13:48.277 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:5
,2016-04-03 21:13:48.278 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,2016-04-03 21:13:48.279 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:5
2016-04-03 21:13:48.279 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-03 21:13:48.282 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
2016-04-03 21:13:48.283 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:13:48.283 ThaliTest[404:406685] multipeer manager: stop client timer
,2016-04-03 21:13:48.284 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:6
2016-04-03 21:13:48.285 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
2016-04-03 21:13:48.286 ThaliTest[404:406685] TH,EMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:6
2016-04-03 21:13:48.286 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-03 21:13:48.620 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-03 21:13:48.622 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:13:48.624 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:13:48.624 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:13:48.625 ThaliTest[404:406685] multipeer manager: stop client timer
,2016-04-03 21:13:48.627 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-03 21:13:49.079 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:13:49.080 ThaliTest[404:406685] THEMultipeerManager stopping peer
2016-04-03 21:13:49.080 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-03 21:13:49.083 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:13:49.084 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:13:49.084 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-03 21:13:49.201 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:13:49.203 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:13:49.205 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:13:49.206 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:13:49.207 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-03 21:13:52.764 ThaliTest[404:406685] jxcore: connect foo
2016-04-03 21:13:52.764 ThaliTest[404:406685] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-03 21:14:33.195 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-03 21:14:33.197 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:14:33.199 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:14:33.200 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:14:33.200 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-03 21:14:33.789 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:14:33.790 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
,2016-04-03 21:14:33.791 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
2016-04-03 21:14:33.791 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:7
2016-04-03 21:14:33.792 Thal,iTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-03 21:14:33.795 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-03 21:14:33.799 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:35.048 ThaliTest[404:406254] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:35.049 ThaliTest[404:406254] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:7
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-03 21:14:35.317 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-03 21:14:35.319 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:14:35.321 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:14:35.322 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:14:35.323 ThaliTest[404:406685] multipeer manager: stop client timer
2016-04-03 21:14:35.323 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-03 21:14:36.357 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:14:36.358 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
,2016-04-03 21:14:36.359 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
2016-04-03 21:14:36.360 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:8
2016-04-03 21:14:36.360 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-03 21:14:36.363 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-03 21:14:36.367 ThaliTest[404:406685] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-03 21:14:37.403 ThaliTest[404:406254] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9C9DAABD-80A6-487A-AC19-4D6E0668D813:7","pleaseConnect":0}]
,2016-04-03 21:14:37.407 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:14:37.408 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:14:37.409 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:14:37.409 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:14:37.584 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:37.584 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F2,2D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:37.701 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:37.701 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F2,2D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:37.704 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:14:37.705 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:38.103 ThaliTest[404:407649] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:38.104 ThaliTest[404:407649] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:14:38.104 T,haliTest[404:407649] client session: disconnect
2016-04-03 21:14:38.104 ThaliTest[404:407649] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:38.105 ThaliTest[404:407649] client session: no connect callback (server initiated)
,2016-04-03 21:14:38.492 ThaliTest[404:406254] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C7015DA-AE07-4F33-B74F-C43FFD219895:8","pleaseConnect":0}]
,2016-04-03 21:14:38.966 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:38.968 ThaliTest[404:406254] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8","pleaseConnect":0}]
,2016-04-03 21:14:40.712 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:40.713 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:14:40.713 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:41.134 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:41.134 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
,2016-04-03 21:14:41.134 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:43.766 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:43.767 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:14:43.767 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:44.277 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:44.277 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:14:44.278 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:46.910 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:46.911 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:14:46.911 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:47.410 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-03 21:14:47.455 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:14:47.456 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
,2016-04-03 21:14:47.456 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:50.092 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:14:50.093 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:14:50.093 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:50.212 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:14:50.212 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
,2016-04-03 21:14:50.213 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:50.424 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:14:50.425 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:14:50.426 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:14:50.426 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:14:50.616 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:50.617 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
,2016-04-03 21:14:50.617 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:51.664 ThaliTest[404:407621] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:14:51.666 ThaliTest[404:407621] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:14:51.666 ThaliTest[404:407621] client session: disconnect
2016-04-03 21:14:51.667 ThaliTest[404:407621] client session: state,Change:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
2016-04-03 21:14:51.667 ThaliTest[404:407621] client session: no connect callback (server initiated)
,2016-04-03 21:14:53.235 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:14:53.236 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:14:53.236 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:53.755 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:14:53.755 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
,2016-04-03 21:14:53.756 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:14:56.361 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:14:56.384 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:14:56.385 ThaliTest[404:406254] client: found updated peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:14:56.385 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9C9DAABD-80A6-487A-AC19-4D6E0668D813:8","pleaseConnect":0}]
,2016-04-03 21:14:56.906 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:14:56.907 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:14:56.907 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:00.427 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:15:01.091 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:15:01.092 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
,2016-04-03 21:15:01.093 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:03.199 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:15:03.199 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
,2016-04-03 21:15:03.200 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:03.432 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:15:03.433 ThaliTest[404:406685] client: server will connect
2016-04-03 21:15:03.434 ThaliTest[404:406685] client session: reverseConnect
2016-04-03 21:15:03.434 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:03.673 ThaliTest[404:407621] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:03.673 ThaliTest[404:407621] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:15:03.675 ThaliTest[404:407621] client session: disconnect
2016-04-03 21:15:03.675 ThaliTest[404:407621] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:03.676 ThaliTest[404:407621] client session: no connect callback (server initiated)
,2016-04-03 21:15:04.180 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:15:04.181 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:15:04.181 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:07.382 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:15:07.382 ThaliTest[404:406254] server: disconnecting to refresh session (9C9DAABD-80A6-487A-AC19-4D6E0668D813)
2016-04-03 21:15:07.383 ThaliTest[404:406254] server: rejecting invitation from 9C9DAABD-80A6-487A-AC19-4D6E0668D813 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:13.435 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:15:16.361 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:15:16.390 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:15:16.390 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:15:16.392 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:16.441 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:15:16.442 ThaliTest[404:406685] client: server will connect
2016-04-03 21:15:16.443 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:15:16.443 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:16.887 ThaliTest[404:407799] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:16.889 ThaliTest[404:407799] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
,2016-04-03 21:15:16.890 ThaliTest[404:407799] client session: disconnect
,2016-04-03 21:15:16.890 ThaliTest[404:407799] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:16.891 ThaliTest[404:407799] client session: no connect callback (server initiated)
,2016-04-03 21:15:26.444 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:15:29.453 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:15:29.454 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:15:29.454 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:15:29.455 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:29.961 ThaliTest[404:407831] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:29.961 ThaliTest[404:407831] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:15:29.961 ThaliTest[404:407831] client session: disconnect
2016-04-03 21:15:29.961 ThaliTest[404:407831] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:29.962 ThaliTest[404:407831] client session: no connect callback (server initiated)
,2016-04-03 21:15:32.552 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:15:32.553 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
2016-04-03 21:15:32.553 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previ,ous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:35.650 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:15:35.651 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:15:35.651 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:36.361 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:15:36.391 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:36.392 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:15:36.392 Th,aliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:15:38.789 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:15:38.789 ThaliTest[404:406254] server: disconnecting to refresh session (CD9AB027-E5E1-43D4-A70E-56CE01144BF3)
,2016-04-03 21:15:38.789 ThaliTest[404:406254] server: rejecting invitation from CD9AB027-E5E1-43D4-A70E-56CE01144BF3 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:8 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:7)
,2016-04-03 21:15:39.456 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:15:42.468 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:15:42.469 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:15:42.470 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:15:42.471 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:43.609 ThaliTest[404:407831] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:43.610 ThaliTest[404:407831] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:15:43.611 ThaliTest[404:407831] client session: disconnect
2016-04-03 21:15:43.611 ThaliTest[404:407831] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:43.612 ThaliTest[404:407831] client session: no connect callback (server initiated)
,2016-04-03 21:15:52.471 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:15:55.476 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:15:55.477 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:15:55.478 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:15:55.479 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:55.677 ThaliTest[404:407886] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:15:55.677 ThaliTest[404:407886] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
,2016-04-03 21:15:55.678 ThaliTest[404:407886] client session: disconnect
2016-04-03 21:15:55.678 ThaliTest[404:407886] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:15:55.679 ThaliTest[404:407886] client session: no connect callback (server initiated)
,2016-04-03 21:15:56.361 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:15:56.389 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:15:56.390 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:15:56.390 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:05.479 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-03 21:16:08.492 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:16:08.492 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:16:08.493 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:16:08.494 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:08.788 ThaliTest[404:407831] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:08.789 ThaliTest[404:407831] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
,2016-04-03 21:16:08.789 ThaliTest[404:407831] client session: disconnect
,2016-04-03 21:16:08.789 ThaliTest[404:407831] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:08.791 ThaliTest[404:407831] client session: no connect callback (server initiated)
,2016-04-03 21:16:16.361 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:16:16.390 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:16.391 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
2016-04-03 21:16:16.391 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:18.494 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:16:21.507 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:16:21.508 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:16:21.509 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:16:21.510 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:21.955 ThaliTest[404:407971] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:21.956 ThaliTest[404:407971] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
2016-04-03 21:16:21.956 T,haliTest[404:407971] client session: disconnect
2016-04-03 21:16:21.956 ThaliTest[404:407971] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:21.958 ThaliTest[404:407971] client session: no connect callback (server initiated)
,2016-04-03 21:16:31.510 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:16:34.523 ThaliTest[404:406685] jxcore: connect 9C9DAABD-80A6-487A-AC19-4D6E0668D813:7
,2016-04-03 21:16:34.524 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:16:34.525 ThaliTest[404:406685] client session: reverseConnect
,2016-04-03 21:16:34.526 ThaliTest[404:406685] client session: stateChange:0->1 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:34.919 ThaliTest[404:408010] client session: not connected 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:34.921 ThaliTest[404:408010] client session: onLinkFailure: 9C9DAABD-80A6-487A-AC19-4D6E0668D813
,2016-04-03 21:16:34.921 ThaliTest[404:408010] client session: disconnect
,2016-04-03 21:16:34.921 ThaliTest[404:408010] client session: stateChange:1->0 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
,2016-04-03 21:16:34.922 ThaliTest[404:408010] client session: no connect callback (server initiated)
,2016-04-03 21:16:36.360 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:16:36.389 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:36.390 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:36.390 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:44.526 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-03 21:16:44.684 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-03 21:16:44.687 ThaliTest[404:406685] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-03 21:16:44.689 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening
,2016-04-03 21:16:44.689 ThaliTest[404:406685] THEMultipeerManager stopping peer
,2016-04-03 21:16:44.691 ThaliTest[404:406685] multipeer manager: stop client timer
,2016-04-03 21:16:44.691 ThaliTest[404:406685] jxcore: stopAdvertisingAndListening: success
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-03 21:16:45.198 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening
,2016-04-03 21:16:45.198 ThaliTest[404:406685] server: starting 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:16:45.199 ThaliTest[404:406685] multipeer manager: start client restart timer: 0x17f4acb0
,2016-04-03 21:16:45.200 ThaliTest[404:406685] THEMultipeerManager initialized peer 569AF1E0-EE92-40BF-918A-581DB52F22D0:9
,2016-04-03 21:16:45.201 ThaliTest[404:406685] jxcore: startUpdateAdvertisingAndListening: success
,ok 180 Can call startUpdateAdvertisingAndListening without error
,2016-04-03 21:16:45.205 ThaliTest[404:406685] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-03 21:16:45.207 ThaliTest[404:406685] j,xcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-03 21:16:46.121 ThaliTest[404:406254] client: found new peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:46.122 ThaliTest[404:406254] client: found new peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:8
,2016-04-03 21:16:46.123 ThaliTest[404:406254] client: found new peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:8
2016-04-03 21:16:46.125 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:46.125 ThaliTest[404:406685] client: server will connect
2016-04-03 21:16:46.127 ThaliTest[404:406685] client session: reverseConnect
2016-04-03 21:16:46.127 ThaliTest[404:406685] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:46.560 ThaliTest[404:408044] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:16:46.560 ThaliTest[404:408044] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:16:46.560 ThaliTest[404:408044] client session: disconnect
,2016-04-03 21:16:46.561 ThaliTest[404:408044] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:46.563 ThaliTest[404:408044] client session: no connect callback (server initiated)
,2016-04-03 21:16:47.696 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:16:47.697 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F2,2D0:9 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:8)
,2016-04-03 21:16:56.128 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-03 21:16:59.140 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:59.141 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:16:59.141 ThaliTest[404:406685] client session: reverseConnect
2016-04-03 21:16:59.142 ThaliTest[404:406685] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:59.931 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:16:59.931 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
,2016-04-03 21:16:59.932 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:9 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:8)
,2016-04-03 21:16:59.963 ThaliTest[404:408058] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:59.963 ThaliTest[404:408058] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:16:59.964 ThaliTest[404:408058] client session: disconnect
,2016-04-03 21:16:59.964 ThaliTest[404:408058] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:16:59.965 ThaliTest[404:408058] client session: no connect callback (server initiated)
,2016-04-03 21:17:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:17:05.224 ThaliTest[404:406254] client: found updated peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:17:05.224 ThaliTest[404:406254] client: found updated peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:05.225 ThaliTest[404:406254] client: found updated peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:09.143 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-03 21:17:12.148 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:12.149 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:17:12.149 ThaliTest[404:406685] client session: reverseConnect
2016-04-03 21:17:12.150 ThaliTest[404:406685] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:12.271 ThaliTest[404:408058] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:12.271 ThaliTest[404:408058] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
2016-04-03 21:17:12.273 ThaliTest[404:408058] client session: disconnect
,2016-04-03 21:17:12.273 ThaliTest[404:408058] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:12.274 ThaliTest[404:408058] client session: no connect callback (server initiated)
,2016-04-03 21:17:12.404 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:17:12.405 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
2016-04-03 21:17:12.405 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:9 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:8)
,2016-04-03 21:17:22.151 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-03 21:17:25.161 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:25.162 ThaliTest[404:406685] client: server will connect
,2016-04-03 21:17:25.163 ThaliTest[404:406685] client session: reverseConnect
2016-04-03 21:17:25.163 ThaliTest[404:406685] client session: stateChange:0->1 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:17:25.234 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:17:25.235 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:17:25.235 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:17:35.164 ThaliTest[404:406254] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-03 21:17:38.177 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:38.178 ThaliTest[404:406685] client: already connect(ing/ed) to CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:38.178 ThaliTest[404:406685] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-03 21:17:38.995 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:17:38.996 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
2016-04-03 21:17:38.996 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:9 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:8)
,2016-04-03 21:17:41.198 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
2016-04-03 21:17:41.198 ThaliTest[404:406685] client: already connect(ing/ed) to CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:41.199 ThaliTest[404:406685] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-03 21:17:44.215 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:44.216 ThaliTest[404:406685] client: already connect(ing/ed) to CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:44.216 ThaliTest[404:406685] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-03 21:17:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:17:45.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:17:45.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:17:45.232 Th,aliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:47.230 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:47.231 ThaliTest[404:406685] client: already connect(ing/ed) to CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:47.231 ThaliTest[404:406685] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-03 21:17:50.252 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:50.253 ThaliTest[404:406685] client: already connect(ing/ed) to CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:50.253 ThaliTest[404:406685] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-03 21:17:51.525 ThaliTest[404:406254] multipeer session: reset timer
2016-04-03 21:17:51.525 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
2016-04-03 21:17:51.526 ThaliTest[404:406254] serve,r: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:9 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:8)
,2016-04-03 21:17:53.272 ThaliTest[404:406685] jxcore: connect CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:53.272 ThaliTest[404:406685] client: already connect(ing/ed) to CD9AB027-E5E1-43D4-A70E-56CE01144BF3:8
,2016-04-03 21:17:53.273 ThaliTest[404:406685] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-03 21:17:58.158 ThaliTest[404:408197] client session: not connected CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:58.159 ThaliTest[404:408197] client session: onLinkFailure: CD9AB027-E5E1-43D4-A70E-56CE01144BF3
,2016-04-03 21:17:58.160 ThaliTest[404:408197] client session: disconnect
,2016-04-03 21:17:58.161 ThaliTest[404:408197] client session: stateChange:1->0 CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:17:58.162 ThaliTest[404:408197] client session: no connect callback (server initiated)
,2016-04-03 21:18:05.010 ThaliTest[404:406254] multipeer session: reset timer
,2016-04-03 21:18:05.011 ThaliTest[404:406254] server: disconnecting to refresh session (4C7015DA-AE07-4F33-B74F-C43FFD219895)
2016-04-03 21:18:05.011 ThaliTest[404:406254] server: rejecting invitation from 4C7015DA-AE07-4F33-B74F-C43FFD219895 due to previous generation (569AF1E0-EE92-40BF-918A-581DB52F22D0:9 != 569AF1E0-EE92-40BF-918A-581DB52F22D0:8)
,2016-04-03 21:18:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:18:05.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:05.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:18:05.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:18:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:18:25.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:18:25.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:25.233 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:18:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:18:45.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:18:45.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:18:45.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:19:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:19:05.229 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:19:05.230 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:19:05.230 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:19:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:19:25.234 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:19:25.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:19:25.235 Th,aliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:19:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:19:45.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:19:45.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:19:45.233 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:20:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:20:05.234 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:20:05.234 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:20:05.235 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:20:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:20:25.230 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:20:25.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:20:25.231 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:20:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:20:45.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:20:45.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:20:45.233 Th,aliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:21:05.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:05.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:21:05.233 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:21:25.230 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:21:25.230 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:21:25.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:21:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:21:45.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:21:45.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:21:45.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:22:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:22:05.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:22:05.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:22:05.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:22:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:22:25.231 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:22:25.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:22:25.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:22:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:22:45.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:22:45.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:22:45.233 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:23:05.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:05.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:23:05.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:23:25.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:23:25.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:23:25.233 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:23:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:23:45.230 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:23:45.230 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:23:45.230 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:24:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:24:05.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:05.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:24:05.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:24:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:24:25.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:24:25.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:24:25.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:24:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:24:45.230 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:24:45.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:24:45.231 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:25:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:25:05.229 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:25:05.230 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:05.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:25:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:25:25.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:25:25.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:25:25.235 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:25:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:25:45.234 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:25:45.234 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:25:45.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:26:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:26:05.233 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:05.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:26:05.233 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:26:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:26:25.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:26:25.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:26:25.233 Th,aliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:26:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:26:45.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:26:45.234 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:26:45.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:27:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:27:05.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:05.234 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:27:05.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:27:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:27:25.231 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:25.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:27:25.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:27:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:27:45.230 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:27:45.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:27:45.231 Th,aliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:28:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:28:05.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:28:05.233 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:05.234 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
,2016-04-03 21:28:25.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:28:25.234 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:28:25.235 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:28:25.235 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
,2016-04-03 21:28:45.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:28:45.231 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:28:45.231 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9
2016-04-03 21:28:45.232 Th,aliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
,2016-04-03 21:29:05.201 ThaliTest[404:406254] multipeer manager: restart client
,2016-04-03 21:29:05.232 ThaliTest[404:406254] client: found existing peer: 9C9DAABD-80A6-487A-AC19-4D6E0668D813:9
2016-04-03 21:29:05.232 ThaliTest[404:406254] client: found existing peer: CD9AB027-E5E1-43D4-A70E-56CE01144BF3:9
2016-04-03 21:29:05.232 ThaliTest[404:406254] client: found existing peer: 4C7015DA-AE07-4F33-B74F-C43FFD219895:9

```
