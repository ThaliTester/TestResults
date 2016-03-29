#### Test 64423763d6e7601_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64423763d6e7601/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7FE295C6-1E6C-4843-8626-43B0C41339D9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7FE295C6-1E6C-4843-8626-43B0C41339D9/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64423763d6e7601/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64423763d6e7601/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56251"
,(lldb)     command script import "/tmp/7FE295C6-1E6C-4843-8626-43B0C41339D9/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-29 09:48:53.195 ThaliTest[1798:4604926] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F76B236A-5452-4F92-AEDC-CBD061D295A4/Library/Cookies/Cookies.binarycookies
,2016-03-29 09:48:53.293 ThaliTest[1798:4604926] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-29 09:48:53.295 ThaliTest[1798:4604926] Multi-tasking -> Device: YES, App: YES
,2016-03-29 09:48:53.313 ThaliTest[1798:4604926] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-29 09:48:54.498 ThaliTest[1798:4604926] Using UIWebView
2016-03-29 09:48:54.501 ThaliTest[1798:4604926] [CDVTimer][handleopenurl] 0.252008ms
,2016-03-29 09:48:54.507 ThaliTest[1798:4604926] [CDVTimer][intentandnavigationfilter] 5.676031ms
2016-03-29 09:48:54.508 ThaliTest[1798:4604926] [CDVTimer][gesturehandler] 0.217974ms
2016-03-29 09:48:54.508 ThaliTest[1798:4604926] [CDVTimer][TotalPluginStartup] 6.956041ms
,2016-03-29 09:48:59.421 ThaliTest[1798:4604926] Resetting plugins due to page load.
,2016-03-29 09:49:01.628 ThaliTest[1798:4604926] Finished load of: file:///var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/index.html
,2016-03-29 09:49:01.826 ThaliTest[1798:4604926] JXcore Cordova plugin initializing
2016-03-29 09:49:01.827 ThaliTest[1798:4605043] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2016-03-29 09:49:15.941 ThaliTest[1798:4605043] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-29 09:49:15.942 ThaliTest[1798:4605043] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-29 09:49:15.943 ThaliTest[1798:4605043] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-29 09:49:15.947 ThaliTest[1798:4605043] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6D76F1E5-DEAA-4E58-A62B-1A9E01E0B313/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54120
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54122
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54125
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54129
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
DEBUG createNativeListener: listening 54134
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
DEBUG createNativeListener: listening 54138
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
DEBUG createNativeListener: listening 54142
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
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54146
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 54150
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
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 54202
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 54206
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
ok 42 incomi,ng has been removed
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
,ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
ok 59 thirdPromise - in resolve
ok 60 secondPromise - second to run
ok 61 secondPromise - in catch
ok 62 firstPromise - third to run
ok 63 firstPromise - in then
ok 64 testing promises
,# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
ok 67 second
ok 68 secondPromise - in then
,ok 69 first
ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
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
,# teardown
,ok 87 error should be null
,ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54218
2016-03-29 09:52:12.411 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: ,{"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:12.412 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
,2016-03-29 09:52:12.415 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-29 09:52:12.417 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
# teardown
,2016-03-29 09:52:12.599 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:12.600 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:52:12.600 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 09:52:12.600 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:12.601 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
,ok 94 error should be null
,# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54220
,2016-03-29 09:52:13.709 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements
,2016-03-29 09:52:13.711 ThaliTest[1798:4605043] multipeer manager: start client restart timer: 0x14d6fb90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:52:13.712 Th,aliTest[1798:4605043] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
2016-03-29 09:52:13.724 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-29 09:52:13.725 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements: success
ok 97 error should be null
ok 98 error should be null
# teardown
,2016-03-29 09:52:33.712 ThaliTest[1798:4604926] multipeer manager: restart client
,2016-03-29 09:52:42.519 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:42.519 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:52:42.519 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 09:52:42.520 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
2016-03-29 09:52:42.520 ThaliTest[1798:4605043] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:42.521 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 99 error should be null
,ok 100 error should be null
,# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54222
,2016-03-29 09:52:49.639 ThaliTest[1798:4605043] jxcore: startUpdateAdvertisingAndListening
2016-03-29 09:52:49.639 ThaliTest[1798:4605043] server: starting 84638737-5933-4323-AFE3-F663D82D6EBD:1
2016-03-29 09:52:49.640 ThaliTest[1798:4605043] multipeer m,anager: start client restart timer: 0x14d6fb90
2016-03-29 09:52:49.640 ThaliTest[1798:4605043] THEMultipeerManager initialized peer 84638737-5933-4323-AFE3-F663D82D6EBD:1
2016-03-29 09:52:49.640 ThaliTest[1798:4605043] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
2016-03-29 09:52:49.653 ThaliTest[1798:4605043] jxcore: startUpdateAdvertisingAndListening
2016-03-29 09:52:49.653 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:52:49.653, ThaliTest[1798:4605043] multipeer manager: stop client timer
2016-03-29 09:52:49.653 ThaliTest[1798:4605043] server: starting 84638737-5933-4323-AFE3-F663D82D6EBD:2
,2016-03-29 09:52:49.654 ThaliTest[1798:4605043] multipeer manager: start client restart timer: 0x14d6fb90
,2016-03-29 09:52:49.661 ThaliTest[1798:4605043] THEMultipeerManager initialized peer 84638737-5933-4323-AFE3-F663D82D6EBD:2
2016-03-29 09:52:49.661 ThaliTest[1798:4605043] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,# teardown
,2016-03-29 09:52:51.013 ThaliTest[1798:4604926] client: found new peer: E64D9D09-7177-4B98-9A96-92B472CDF1BB:2
,2016-03-29 09:52:54.778 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:54.778 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:52:54.779 ThaliTest[1798:4605043] multipeer manager: stop client timer
2016-03-29 09:52:54.779 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:52:54.779 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:54.780 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54227
,2016-03-29 09:52:56.460 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
,2016-03-29 09:52:56.461 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
,2016-03-29 09:52:56.462 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: success
,ok 107 error should be null
,ok 108 error should be null
,2016-03-29 09:52:56.465 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
,2016-03-29 09:52:56.466 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
,2016-03-29 09:52:56.467 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,# teardown
,2016-03-29 09:52:58.840 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:52:58.840 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:52:58.840 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 09:52:58.841 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:52:58.842 ThaliTest[1798,:4605043] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 54229
ok 113 first call should succeed
,ok 114 first call should succeed
,ok 115 specific error should be returned
# teardown
,2016-03-29 09:53:04.849 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:53:04.849 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:53:04.849 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-29 09:53:04.849 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:53:04.850 ThaliTest[1798,:4605043] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 54231
2016-03-29 09:53:05.368 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements
2016-03-29 09:53:05.368 ThaliTest[1798:4605043] multipeer manager: start client restart timer: 0x14d6fb90
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:53:05.369 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements: success
,2016-03-29 09:53:05.391 ThaliTest[1798:4605043] jxcore: startUpdateAdvertisingAndListening
,2016-03-29 09:53:05.392 ThaliTest[1798:4605043] server: starting 84638737-5933-4323-AFE3-F663D82D6EBD:3
,2016-03-29 09:53:05.395 ThaliTest[1798:4605043] THEMultipeerManager initialized peer 84638737-5933-4323-AFE3-F663D82D6EBD:3
,2016-03-29 09:53:05.399 ThaliTest[1798:4605043] jxcore: startUpdateAdvertisingAndListening: success
,ok 118 called only once
,ok 119 discovery state matches
,ok 120 advertising state matches
,# teardown
,2016-03-29 09:53:05.519 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:53:05.519 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:53:05.519 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: success
2016-03-29 09:53:05.520 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
2016-03-29 09:53:05.520 ThaliTest[1798:4605043] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-29 09:53:05.521 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 121 error should be null
ok 122 error should be null
# setup
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
ok 133 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 134 error should be null
ok 135 error should be null
# setup
,# 35. Can call start/stopListeningForAdvertisements
,2016-03-29 09:53:45.827 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements
2016-03-29 09:53:45.827 ThaliTest[1798:4605043] multipeer manager: start client restart timer: 0x14d6fb90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:53:45.829 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error
2016-03-29 09:53:45.830 ThaliTes,t[1798:4605043] jxcore: stopListeningForAdvertisements
2016-03-29 09:53:45.830 ThaliTest[1798:4605043] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-29 09:53:45.831 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
ok 137 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-29 09:53:46.092 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-29 09:53:46.093 ThaliTest[1798:46050,43] jxcore: stopListeningForAdvertisements: success
ok 138 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-29 09:53:46.095 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening
2016-03-29 09:53:46.095 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:53:46.095 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: success
ok 139 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-29 09:53:46.833 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements
2016-03-29 09:53:46.833 ThaliTest[1798:4605043] multipeer manager: start client restart timer: 0x14d6fb90
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:53:46.834 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error
2016-03-29 09:53:46.836 ThaliTes,t[1798:4605043] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-29 09:53:46.837 ThaliTest[1798:4605043] jxcore: startListeningForAdvertisements: success
ok 141 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-29 09:54:06.835 ThaliTest[1798:4604926] multipeer manager: restart client
,2016-03-29 09:54:07.173 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements
2016-03-29 09:54:07.174 ThaliTest[1798:4605043] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-29 09:54:07.175 ThaliTest[1798:4605043] jxcore: stopListeningForAdvertisements: success
ok 142 Should be able to call stopListeningForAdvertisments in teardown
2016-03-29 09:54:07.176 ThaliTest[1798:46050,43] jxcore: stopAdvertisingAndListening
2016-03-29 09:54:07.176 ThaliTest[1798:4605043] THEMultipeerManager stopping peer
2016-03-29 09:54:07.176 ThaliTest[1798:4605043] jxcore: stopAdvertisingAndListening: success
ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup

```
