#### Test 64613803d18c8d9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/823AD709-248B-4994-B87A-19D449A3FE7A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/823AD709-248B-4994-B87A-19D449A3FE7A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64613803d18c8d9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50050"
,(lldb)     command script import "/tmp/823AD709-248B-4994-B87A-19D449A3FE7A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 07:17:37.167 ThaliTest[257:72559] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9E919083-0E61-4640-8B46-50D57A6CBA55/Library/Cookies/Cookies.binarycookies
,2016-04-01 07:17:37.532 ThaliTest[257:72559] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 07:17:37.533 ThaliTest[257:72559] Multi-tasking -> Device: YES, App: YES
,2016-04-01 07:17:37.550 ThaliTest[257:72559] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 07:17:39.779 ThaliTest[257:72559] Using UIWebView
,2016-04-01 07:17:39.786 ThaliTest[257:72559] [CDVTimer][handleopenurl] 0.423968ms
,2016-04-01 07:17:39.793 ThaliTest[257:72559] [CDVTimer][intentandnavigationfilter] 6.558001ms
,2016-04-01 07:17:39.794 ThaliTest[257:72559] [CDVTimer][gesturehandler] 0.306964ms
,2016-04-01 07:17:39.794 ThaliTest[257:72559] [CDVTimer][TotalPluginStartup] 8.952975ms
,2016-04-01 07:17:47.749 ThaliTest[257:72559] Resetting plugins due to page load.
,2016-04-01 07:17:51.970 ThaliTest[257:72559] Finished load of: file:///var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/index.html
,2016-04-01 07:17:52.184 ThaliTest[257:72559] JXcore Cordova plugin initializing
,2016-04-01 07:17:52.185 ThaliTest[257:72810] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 07:17:58.723 ThaliTest[257:72810] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 07:17:58.723 ThaliTest[257:72810] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 07:17:58.724 ThaliTest[257:72810] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-01 07:17:58.725 ThaliTest[257:72810] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/477D5E3F-9EC1-413C-AAC4-616A249478DF/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-01 07:18:03.962 ThaliTest[257:72559] THREAD WARNING: ['JXcore'] took '4959.288818' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49687
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49689
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
,DEBUG createNativeListener: listening 49692
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
,DEBUG createNativeListener: listening 49696
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
,DEBUG createNativeListener: listening 49701
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
,DEBUG createNativeListener: listening 49705
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
,DEBUG createNativeListener: listening 49709
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
,DEBUG createNativeListener: listening 49713
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
,DEBUG createNativeListener: listening 49717
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
,DEBUG createNativeListener: listening 49769
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
,DEBUG createNativeListener: listening 49773
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
,[{"uuid":"fb907fa7-6bbb-4685-a83b-630e712f1cec","data":"custom data"},{"uuid":"2116515a-89f8-4ac6-81c4-f1910b261345","data":"custom data"},{"uuid":"0aa21398-7b4c-4999-b9cc-207fff665ddf","data":"custom data"},{"uuid":"096b47f0-b3ca-42e2-86de-efb223a755a4","data":"custom data"}]
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
,DEBUG createNativeListener: listening 49783
,2016-04-01 07:20:44.345 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:20:44.346 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-01 07:20:44.348 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:20:44.349 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-01 07:20:44.540 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:44.540 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:20:44.540 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,2016-04-01 07:20:44.541 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:20:44.542 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49785
,2016-04-01 07:20:44.805 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,2016-04-01 07:20:44.807 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 07:20:44.810 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-01 07:20:44.834 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 07:20:44.837 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-01 07:20:45.130 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:20:45.131 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:20:45.131 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,2016-04-01 07:20:45.132 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,2016-04-01 07:20:45.133 ThaliTest[257:72810] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:20:45.136 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49787
,2016-04-01 07:20:45.690 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 07:20:45.691 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:1
,2016-04-01 07:20:45.692 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,2016-04-01 07:20:45.693 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:1
2016-04-01 07:20:45.693 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-01 07:20:45.710 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:20:45.711 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:20:45.711 ThaliTest[257:72810] multipeer manager: stop client timer
2016-04-01 07:20:45.712 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:2
,2016-04-01 07:20:45.714 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
2016-04-01 07:20:45.715 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:2
2016-04-01 07:20:45.715 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-01 07:20:46.335 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:46.335 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:20:46.335 ThaliTest[257:72810] multipeer manager: stop client timer
2016-04-01 07:20:46.336 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
2016-04-01 07:20:46.337 ThaliTest[257:72810] jxcore: stopListeningForAdvertisement,s
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 07:20:46.340 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49792
,2016-04-01 07:20:48.375 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:20:48.375 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:20:48.376 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-01 07:20:48.383 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
2016-04-01 07:20:48.383 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:20:48.383 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-01 07:21:03.696 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:03.696 ThaliTest[257:72810] THEMultipeerManager stopping peer
2016-04-01 07:21:03.696 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,2016-04-01 07:21:03.697 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:03.700 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49794
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-01 07:21:06.152 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:06.152 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:06.153 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,2016-04-01 07:21:06.154 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:06.157 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49796
,2016-04-01 07:21:06.396 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,2016-04-01 07:21:06.398 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 07:21:06.405 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
,2016-04-01 07:21:06.426 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 07:21:06.427 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:3
,2016-04-01 07:21:06.428 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:3
,2016-04-01 07:21:06.430 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-01 07:21:06.830 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:06.831 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:06.832 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,2016-04-01 07:21:06.834 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,2016-04-01 07:21:06.837 ThaliTest[257:72810] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:06.840 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
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
,2016-04-01 07:21:41.869 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,2016-04-01 07:21:41.870 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:41.873 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
,2016-04-01 07:21:41.878 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:41.879 ThaliTest[257:72810] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:41.881 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-01 07:21:42.174 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:42.176 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:42.179 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:42.180 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:42.180 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 07:21:42.843 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,2016-04-01 07:21:42.843 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 07:21:42.846 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
,2016-04-01 07:21:42.850 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 07:21:42.852 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-01 07:21:43.811 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
2016-04-01 07:21:43.812 ThaliTest[257:72810] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:43.815 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:43.817 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:43.817 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:43.818 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 07:21:44.830 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:44.833 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-01 07:21:44.835 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:44.837 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-01 07:21:44.965 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:44.968 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:44.970 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:44.971 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:44.972 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 07:21:45.336 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 07:21:45.337 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:4
,2016-04-01 07:21:45.338 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,2016-04-01 07:21:45.338 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:4
,2016-04-01 07:21:45.339 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:45.344 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
2016-04-01 07:21:45.344 ThaliTest[257:72810] THEMultipeerManager stopping peer
2016-04-01 07:21:45.345 ThaliTest[257:72810] multipeer manager: stop client timer
2016-04-01 07:21:45.345 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 07:21:45.449 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:21:45.452 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:45.454 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:45.455 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:45.456 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 07:21:45.833 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 07:21:45.834 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:5
,2016-04-01 07:21:45.835 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
2016-04-01 07:21:45.835 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:5
2016-04-01 07:21:45.836 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
,ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 07:21:45.839 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:21:45.839 ThaliTest[257:72810] THEMultipeerManager stopping peer
2016-04-01 07:21:45.8,40 ThaliTest[257:72810] multipeer manager: stop client timer
2016-04-01 07:21:45.840 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:6
,2016-04-01 07:21:45.841 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
,2016-04-01 07:21:45.841 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:6
,2016-04-01 07:21:45.842 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-04-01 07:21:45.957 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:21:45.960 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:21:45.962 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:45.963 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:45.963 ThaliTest[257:72810] multipeer manager: stop client timer
2016-04-01 07:21:45.964 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 07:21:48.074 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:48.075 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:48.075 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 07:21:48.079 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:21:48.079 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:21:48.080 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-01 07:22:08.920 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:22:08.923 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:22:08.925 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:22:08.926 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:22:08.926 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 07:22:20.198 ThaliTest[257:72810] jxcore: connect foo
2016-04-01 07:22:20.199 ThaliTest[257:72810] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-01 07:22:20.401 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 07:22:20.403 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:22:20.406 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:22:20.406 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:22:20.407 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 07:22:21.141 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:21.142 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
,2016-04-01 07:22:21.143 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
2016-04-01 07:22:21.144 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:7
,2016-04-01 07:22:21.144 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-01 07:22:21.150 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-01 07:22:21.153 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:22.193 ThaliTest[257:72559] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:22.193 ThaliTest[257:72559] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-01 07:22:22.523 ThaliTest[257:72559] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,2016-04-01 07:22:24.161 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:22:24.163 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:22:24.166 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:22:24.166 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:22:24.167 ThaliTest[257:72810] multipeer manager: stop client timer
2016-04-01 07:22:24.168 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-01 07:22:25.286 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
2016-04-01 07:22:25.287 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
,2016-04-01 07:22:25.288 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
2016-04-01 07:22:25.288 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:8
2016-04-01 07:22:25.288 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 07:22:25.292 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:22:25.294 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 07:22:26.103 ThaliTest[257:72559] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:26.104 ThaliTest[257:72559] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A956A86E-53B4-4DBF-B193-1271D200C497:7","pleaseConnect":0}]
,2016-04-01 07:22:26.109 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:26.110 ThaliTest[257:72810] client: server will connect
2016-04-01 07:22:26.110 ThaliTest[257:72810] client session: reverseConnect
,2016-04-01 07:22:26.111 ThaliTest[257:72810] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"15037E99-B9A2-4986-82B2-3AB5B64E2CE2:7","pleaseConnect":0}]
,2016-04-01 07:22:26.519 ThaliTest[257:72559] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:7","pleaseConnect":0}]
,2016-04-01 07:22:27.623 ThaliTest[257:73426] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:27.626 ThaliTest[257:73426] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:22:27.626 Tha,liTest[257:73426] client session: disconnect
2016-04-01 07:22:27.626 ThaliTest[257:73426] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:27.628 ThaliTest[257:73426] client session: no connect callback (server initiated)
,2016-04-01 07:22:36.112 ThaliTest[257:72559] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:22:39.123 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:39.125 ThaliTest[257:72810] client: server will connect
2016-04-01 07:22:39.125 ThaliTest[257:72810] client session: reverseConnect
,2016-04-01 07:22:39.125 ThaliTest[257:72810] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:39.307 ThaliTest[257:73490] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:39.307 ThaliTest[257:73490] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:22:39.307 Tha,liTest[257:73490] client session: disconnect
2016-04-01 07:22:39.308 ThaliTest[257:73490] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:22:39.308 ThaliTest[257:73490] client session: no connect callback (server initiated)
,2016-04-01 07:22:45.290 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:22:45.318 ThaliTest[257:72559] client: found updated peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:22:45.319 ThaliTest[257:72559] client: found updated peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:22:45.321 ThaliTest[257:72559] client: found updated peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"A956A86E-53B4-4DBF-B193-1271D200C497:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"444A455A-C80E-416D-9E03-5D6FFDE7B60A:8","pleaseConnect":0}]
,2016-04-01 07:22:49.127 ThaliTest[257:72559] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 07:22:52.134 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:22:52.135 ThaliTest[257:72810] client: server will connect
,2016-04-01 07:22:52.136 ThaliTest[257:72810] client session: reverseConnect
2016-04-01 07:22:52.136 ThaliTest[257:72810] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:22:52.663 ThaliTest[257:73490] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:22:52.664 ThaliTest[257:73490] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:22:52.665 ThaliTest[257:73490] client session: disconnect
,2016-04-01 07:22:52.666 ThaliTest[257:73490] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:22:52.667 ThaliTest[257:73490] client session: no connect callback (server initiated)
,2016-04-01 07:23:02.136 ThaliTest[257:72559] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 07:23:05.143 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:05.143 ThaliTest[257:72810] client: server will connect
,2016-04-01 07:23:05.145 ThaliTest[257:72810] client session: reverseConnect
,2016-04-01 07:23:05.145 ThaliTest[257:72810] client session: stateChange:0->1 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:23:05.289 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:23:05.318 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:05.318 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:05.319 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:23:15.145 ThaliTest[257:72559] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 07:23:18.154 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:18.155 ThaliTest[257:72810] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:18.156 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:23:21.167 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:21.168 ThaliTest[257:72810] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:21.169 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 07:23:24.185 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:24.185 ThaliTest[257:72810] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:24.186 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 07:23:25.290 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:23:25.320 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:25.320 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:25.321 Thal,iTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:23:27.200 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:27.201 ThaliTest[257:72810] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:27.201 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 07:23:30.218 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:30.220 ThaliTest[257:72810] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:30.220 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 07:23:33.233 ThaliTest[257:72810] jxcore: connect A956A86E-53B4-4DBF-B193-1271D200C497:7
2016-04-01 07:23:33.234 ThaliTest[257:72810] client: already connect(ing/ed) to A956A86E-53B4-4DBF-B193-1271D200C497:7
,2016-04-01 07:23:33.235 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-01 07:23:38.117 ThaliTest[257:73687] client session: not connected A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:38.118 ThaliTest[257:73687] client session: onLinkFailure: A956A86E-53B4-4DBF-B193-1271D200C497
2016-04-01 07:23:38.118 ThaliTest[257:73687] client session: disconnect
2016-04-01 07:23:38.118 ThaliTest[257:73687] client session: stateChange:1->0 A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:23:38.119 ThaliTest[257:73687] client session: no connect callback (server initiated)
,2016-04-01 07:23:45.289 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:23:45.322 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:23:45.323 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
2016-04-01 07:23:45.323 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:05.290 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:24:05.347 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 07:24:05.349 ThaliTest[257:72810] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 07:24:05.351 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening
,2016-04-01 07:24:05.352 ThaliTest[257:72810] THEMultipeerManager stopping peer
,2016-04-01 07:24:05.353 ThaliTest[257:72810] multipeer manager: stop client timer
,2016-04-01 07:24:05.353 ThaliTest[257:72810] jxcore: stopAdvertisingAndListening: success
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-01 07:24:07.454 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 07:24:07.455 ThaliTest[257:72810] server: starting 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
,2016-04-01 07:24:07.456 ThaliTest[257:72810] multipeer manager: start client restart timer: 0x17ddb1e0
2016-04-01 07:24:07.457 ThaliTest[257:72810] THEMultipeerManager initialized peer 775127D1-BE71-46C7-B433-2FA7873DBB8C:9
2016-04-01 07:24:07.457 ThaliTest[257:72810] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
,2016-04-01 07:24:07.461 ThaliTest[257:72810] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-01 07:24:07.462 ThaliTest[257:72810] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-01 07:24:07.895 ThaliTest[257:72559] client: found new peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:07.898 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:07.898 ThaliTest[257:72810] client session: connect
2016-04-01 07:24:07.899 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:09.531 ThaliTest[257:72559] client: found new peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:8
,2016-04-01 07:24:10.143 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:24:10.144 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:24:10.724 ThaliTest[257:72559] client: found new peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:24:11.084 ThaliTest[257:73864] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:11.084 ThaliTest[257:73864] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:11.085 ThaliTest[257:73864] client session: disconnect
2016-04-01 07:24:11.086 ThaliTest[257:73864] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:11.087 ThaliTest[257:73864] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:11.087 ThaliTest[257:73864] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 07:24:13.958 ThaliTest[257:72559] multipeer session: reset timer
2016-04-01 07:24:13.959 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
,2016-04-01 07:24:13.959 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:24:14.102 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:14.103 ThaliTest[257:72810] client session: connect
2016-04-01 07:24:14.104 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:16.542 ThaliTest[257:73847] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:16.543 ThaliTest[257:73847] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:24:16.543 ThaliTest[257:73847] client session: disconnect
2016-04-01 07:24:16.544 ThaliTest[257:73847] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:16.545 ThaliTest[257:73847] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:16.546 ThaliTest[257:73847] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 07:24:17.575 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:24:17.576 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:24:17.576 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:24:19.557 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:19.558 ThaliTest[257:72810] client session: connect
,2016-04-01 07:24:19.558 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:21.238 ThaliTest[257:72559] multipeer session: reset timer
2016-04-01 07:24:21.238 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:24:21.239 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:24:23.366 ThaliTest[257:73899] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:23.367 ThaliTest[257:73899] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:24:23.368 ThaliTest[257:73899] client session: disconnect
2016-04-01 07:24:23.369 ThaliTest[257:73899] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
2016-04-01 07:24:23.369 ThaliTest[257:73899] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:24:23.370 ThaliTest[257:73899] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 07:24:24.984 ThaliTest[257:72559] multipeer session: reset timer
2016-04-01 07:24:24.984 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
,2016-04-01 07:24:24.985 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:24:26.375 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:26.376 ThaliTest[257:72810] client session: connect
,2016-04-01 07:24:26.377 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:24:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:24:27.486 ThaliTest[257:72559] client: found updated peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:24:27.486 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
,2016-04-01 07:24:27.489 ThaliTest[257:72559] client: found updated peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:24:27.975 ThaliTest[257:72559] multipeer session: reset timer
2016-04-01 07:24:27.976 ThaliTest[257:72559] server: rejecting invitation for lexical ordering 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:41.803 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:24:41.803 ThaliTest[257:72559] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
,2016-04-01 07:24:41.804 ThaliTest[257:72559] server: rejecting invitation for lexical ordering 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:24:47.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:24:47.489 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:8
2016-04-01 07:24:47.489 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:24:53.800 ThaliTest[257:72559] multipeer session: reset timer
2016-04-01 07:24:53.801 ThaliTest[257:72559] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
2016-04-01 07:24:53.801 ThaliTest[257:72559] server: rejecting invitation for lexical ordering 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:59.352 ThaliTest[257:74011] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:24:59.352 ThaliTest[257:74011] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:24:59.353 ThaliTest[257:74011] client session: disconnect
,2016-04-01 07:24:59.353 ThaliTest[257:74011] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:24:59.354 ThaliTest[257:74011] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:24:59.355 ThaliTest[257:74011] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-01 07:25:02.361 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:25:02.362 ThaliTest[257:72810] client session: connect
,2016-04-01 07:25:02.362 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:04.720 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:25:04.720 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
,2016-04-01 07:25:04.720 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:25:05.074 ThaliTest[257:73996] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:05.074 ThaliTest[257:73996] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:25:05.074 ThaliTest[257:73996] client session: disconnect
,2016-04-01 07:25:05.075 ThaliTest[257:73996] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:05.075 ThaliTest[257:73996] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:05.076 ThaliTest[257:73996] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 07:25:06.642 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:25:06.643 ThaliTest[257:72559] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
,2016-04-01 07:25:06.643 ThaliTest[257:72559] server: rejecting invitation for lexical ordering 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:25:07.488 ThaliTest[257:72559] client: found updated peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:25:07.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:07.492 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:25:08.081 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:25:08.081 ThaliTest[257:72810] client session: connect
,2016-04-01 07:25:08.082 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:10.504 ThaliTest[257:74011] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:10.504 ThaliTest[257:74011] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:10.506 ThaliTest[257:74011] client session: disconnect
,2016-04-01 07:25:10.506 ThaliTest[257:74011] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:10.507 ThaliTest[257:74011] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:25:10.508 ThaliTest[257:74011] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 07:25:13.523 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:25:13.524 ThaliTest[257:72810] client session: connect
2016-04-01 07:25:13.525 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:16.370 ThaliTest[257:73996] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:16.371 ThaliTest[257:73996] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:16.371 ThaliTest[257:73996] client session: disconnect
2016-04-01 07:25:16.371 ThaliTest[257:73996] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:16.373 ThaliTest[257:73996] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:16.373 ThaliTest[257:73996] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 07:25:19.387 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:25:19.388 ThaliTest[257:72810] client session: connect
2016-04-01 07:25:19.388 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:19.951 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:25:19.952 ThaliTest[257:72559] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
,2016-04-01 07:25:19.952 ThaliTest[257:72559] server: rejecting invitation for lexical ordering 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:21.510 ThaliTest[257:74056] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:21.512 ThaliTest[257:74056] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:21.512 ThaliTest[257:74056] client session: disconnect
,2016-04-01 07:25:21.513 ThaliTest[257:74056] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:21.514 ThaliTest[257:74056] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:25:21.514 ThaliTest[257:74056] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 07:25:24.520 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:25:24.521 ThaliTest[257:72810] client session: connect
,2016-04-01 07:25:24.522 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:26.763 ThaliTest[257:74073] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:26.764 ThaliTest[257:74073] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:26.765 ThaliTest[257:74073] client session: disconnect
,2016-04-01 07:25:26.766 ThaliTest[257:74073] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:26.767 ThaliTest[257:74073] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:26.767 ThaliTest[257:74073] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 07:25:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:25:27.491 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:25:27.491 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:25:27.492 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:29.773 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:8
,2016-04-01 07:25:29.774 ThaliTest[257:72810] client session: connect
,2016-04-01 07:25:29.774 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:30.423 ThaliTest[257:74171] client session: not connected 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:30.423 ThaliTest[257:74171] client session: onLinkFailure: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:30.424 ThaliTest[257:74171] client session: disconnect
,2016-04-01 07:25:30.425 ThaliTest[257:74171] client session: stateChange:1->0 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:30.426 ThaliTest[257:74171] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:30.426 ThaliTest[257:74171] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-01 07:25:33.007 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:25:33.007 ThaliTest[257:72559] server: disconnecting to refresh session (15037E99-B9A2-4986-82B2-3AB5B64E2CE2)
,2016-04-01 07:25:33.008 ThaliTest[257:72559] server: rejecting invitation for lexical ordering 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
2016-04-01 07:25:33.010 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:33.010 ThaliTest[257:72810] client session: connect
2016-04-01 07:25:33.010 ThaliTest[257:72810] client session: stateChange:0->1 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:38.612 ThaliTest[257:74171] client session: p2p link connected
,2016-04-01 07:25:38.624 ThaliTest[257:74171] client session: stateChange:1->2 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:38.625 ThaliTest[257:74171] client session: fireConnectCallback: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2
,2016-04-01 07:25:38.625 ThaliTest[257:74171] jxcore: connect: success
,2016-04-01 07:25:38.641 ThaliTest[257:72559] client: relay established
2016-04-01 07:25:38.642 ThaliTest[257:72559] client: new accepted socket: 0x1aa98090
2016-04-01 07:25:38.642 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:38.643 ThaliTest[257:72810] client: already connect(ing/ed) to 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:25:38.644 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,ok 182 Expected error
,ok 183 Null connection as expected
,2016-04-01 07:25:38.647 ThaliTest[257:72810] jxcore: connect 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:38.648 ThaliTest[257:72810] client: already connect(ing/ed) to 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:38.648 ThaliTest[257:72810] jxcore: connect: fail: Already connect(ing/ed)
,ok 184 Expected error
,ok 185 Null connection as expected
,# teardown
,2016-04-01 07:25:44.648 ThaliTest[257:72559] multipeer session: reset timer
2016-04-01 07:25:44.648 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
2016-04-01 07:25:44.649 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:25:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:25:47.487 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:25:47.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:25:47.493 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:25:48.307 ThaliTest[257:72559] multipeer session: reset timer
,2016-04-01 07:25:48.308 ThaliTest[257:72559] server: disconnecting to refresh session (A956A86E-53B4-4DBF-B193-1271D200C497)
,2016-04-01 07:25:48.308 ThaliTest[257:72559] server: rejecting invitation from A956A86E-53B4-4DBF-B193-1271D200C497 due to previous generation (775127D1-BE71-46C7-B433-2FA7873DBB8C:9 != 775127D1-BE71-46C7-B433-2FA7873DBB8C:8)
,2016-04-01 07:26:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:26:07.491 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:26:07.492 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:26:07.493 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:26:27.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:27.489 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:26:27.490 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:26:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:26:47.487 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:26:47.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:26:47.488 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:27:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:27:07.490 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:27:07.490 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:07.491 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:27:27.490 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:27:27.490 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:27:27.491 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:27:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:27:47.488 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:27:47.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:27:47.490 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:28:07.488 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:28:07.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:07.489 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:28:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:28:27.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:28:27.490 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:28:27.490 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:28:47.459 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:28:47.492 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:28:47.493 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:28:47.494 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:29:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:29:07.483 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:29:07.483 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:07.485 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:29:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:29:27.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:27.487 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:29:27.489 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:29:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:29:47.487 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:29:47.488 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:29:47.488 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:30:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:30:07.487 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:30:07.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:30:07.490 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:30:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:30:27.488 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:30:27.488 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:30:27.489 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:30:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:30:47.492 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:30:47.492 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:30:47.492 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:31:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:31:07.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:07.489 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:31:07.491 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:31:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:31:27.490 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:31:27.490 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:27.491 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:31:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:31:47.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:31:47.487 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:31:47.488 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:32:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:32:07.487 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:07.488 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:32:07.488 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:32:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:32:27.490 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:27.491 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:32:27.491 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:32:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:32:47.489 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:32:47.490 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:32:47.490 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:33:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:33:07.487 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:33:07.488 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:33:07.488 Thal,iTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:33:27.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:33:27.488 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:33:27.489 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:33:27.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:33:47.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:33:47.489 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:33:47.489 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:33:47.489 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:34:07.458 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:34:07.490 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:34:07.490 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:34:07.490 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:34:27.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:34:27.476 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:34:27.477 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:34:27.479 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:34:47.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:34:47.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:34:47.475 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:34:47.477 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:35:07.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:35:07.473 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:07.476 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:35:07.476 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:35:27.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:35:27.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:27.475 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:35:27.476 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:35:47.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:35:47.475 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:35:47.476 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:35:47.479 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:36:07.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:36:07.475 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:36:07.475 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:36:07.476 Thal,iTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:36:27.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:36:27.475 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:36:27.475 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:36:27.476 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:36:47.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:36:47.477 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:36:47.477 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:36:47.478 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:07.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:37:07.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:37:07.474 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:37:07.474 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:27.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:37:27.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:37:27.474 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:37:27.476 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:37:47.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:37:47.474 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:37:47.475 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:37:47.475 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:38:07.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:38:07.474 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:38:07.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:38:07.476 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:27.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:38:27.474 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:38:27.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
,2016-04-01 07:38:27.477 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:38:47.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:38:47.474 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9
2016-04-01 07:38:47.474 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
,2016-04-01 07:38:47.476 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
,2016-04-01 07:39:07.444 ThaliTest[257:72559] multipeer manager: restart client
,2016-04-01 07:39:07.475 ThaliTest[257:72559] client: found existing peer: A956A86E-53B4-4DBF-B193-1271D200C497:9
2016-04-01 07:39:07.475 ThaliTest[257:72559] client: found existing peer: 444A455A-C80E-416D-9E03-5D6FFDE7B60A:9
2016-04-01 07:39:07.476 ThaliTest[257:72559] client: found existing peer: 15037E99-B9A2-4986-82B2-3AB5B64E2CE2:9

```
