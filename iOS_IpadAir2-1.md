#### Test 63848581358a1d8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3F268FF7-79F6-4F98-8A44-97031BD87B78/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3F268FF7-79F6-4F98-8A44-97031BD87B78/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63848581358a1d8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55180"
,(lldb)     command script import "/tmp/3F268FF7-79F6-4F98-8A44-97031BD87B78/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 11:45:37.886 ThaliTest[2076:3553059] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E85C2CBA-FCF9-41DA-8BC5-616F76B43FCB/Library/Cookies/Cookies.binarycookies
,2016-03-23 11:45:38.313 ThaliTest[2076:3553059] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 11:45:38.314 ThaliTest[2076:3553059] Multi-tasking -> Device: YES, App: YES
,2016-03-23 11:45:38.332 ThaliTest[2076:3553059] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 11:45:40.233 ThaliTest[2076:3553059] Using UIWebView
,2016-03-23 11:45:40.240 ThaliTest[2076:3553059] [CDVTimer][handleopenurl] 0.422001ms
,2016-03-23 11:45:40.248 ThaliTest[2076:3553059] [CDVTimer][intentandnavigationfilter] 6.709993ms
,2016-03-23 11:45:40.248 ThaliTest[2076:3553059] [CDVTimer][gesturehandler] 0.324011ms
,2016-03-23 11:45:40.249 ThaliTest[2076:3553059] [CDVTimer][TotalPluginStartup] 9.059012ms
,2016-03-23 11:45:47.922 ThaliTest[2076:3553059] Resetting plugins due to page load.
,2016-03-23 11:45:51.580 ThaliTest[2076:3553059] Finished load of: file:///var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/index.html
,2016-03-23 11:45:51.798 ThaliTest[2076:3553059] JXcore Cordova plugin initializing
,2016-03-23 11:45:51.799 ThaliTest[2076:3553294] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 11:45:58.262 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:45:58.263 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:45:58.263 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:45:58.265 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C49BD790-9B69-455F-99D2-3C45A3ECA43E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 11:46:03.512 ThaliTest[2076:3553059] THREAD WARNING: ['JXcore'] took '4971.492920' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51368
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51370
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
,DEBUG createNativeListener: listening 51373
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
,DEBUG createNativeListener: listening 51377
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
,DEBUG createNativeListener: listening 51382
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
,DEBUG createNativeListener: listening 51386
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
,DEBUG createNativeListener: listening 51390
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
,DEBUG createNativeListener: listening 51394
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
,DEBUG createNativeListener: listening 51398
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
,DEBUG createNativeListener: listening 51450
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
,DEBUG createNativeListener: listening 51454
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
,ok 87 error should be null
,# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51466
,2016-03-23 11:48:06.656 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:06.659 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-23 11:48:06.665 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:06.667 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-23 11:48:06.801 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:06.801 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:06.801 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:06.803 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:06.805 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51468
,2016-03-23 11:48:07.122 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:07.123 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:07.126 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-23 11:48:07.153 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:07.155 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-23 11:48:07.493 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:07.493 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:07.494 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:07.495 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,2016-03-23 11:48:07.496 ThaliTest[2076:3553294] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:07.499 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51470
,2016-03-23 11:48:10.138 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:10.139 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:1
,2016-03-23 11:48:10.141 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:48:10.142 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:1
2016-03-23 11:48:10.142 ,ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-23 11:48:10.168 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:10.168 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:10.169 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:48:10.170 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:2
,2016-03-23 11:48:10.172 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:48:10.173 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:2
2016-03-23 11:48:10.174 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-23 11:48:11.455 ThaliTest[2076:3553059] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:2
,2016-03-23 11:48:12.817 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:12.817 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:12.818 ThaliTest[2076:3553294] multipeer manager: stop client timer
,2016-03-23 11:48:12.819 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:48:12.820 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:12.823 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51475
,2016-03-23 11:48:29.602 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:29.603 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:29.603 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,2016-03-23 11:48:29.610 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:29.610 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:29.611 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-23 11:48:31.778 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:31.778 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
2016-03-23 11:48:31.779 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:31.780 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:31.782 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51477
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-23 11:48:34.223 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:34.224 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:34.224 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:48:34.225 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:34.228 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51479
,2016-03-23 11:48:37.411 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:37.412 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:37.415 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:48:37.434 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:37.435 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:3
,2016-03-23 11:48:37.436 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:3
2016-03-23 11:48:37.436 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-23 11:48:37.695 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:37.695 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:37.696 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:48:37.697 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
2016-03-23 11:48:37.698 ThaliTest[2076:3553294] multipeer manager: stop cl,ient timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:37.701 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,ok 128 error should be null
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
,2016-03-23 11:48:46.461 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:46.462 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:48:46.467 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:46.471 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,2016-03-23 11:48:46.472 ThaliTest[2076:3553294] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:46.475 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-23 11:48:46.704 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:46.706 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:46.709 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:46.710 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:46.710 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-23 11:48:47.391 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:48:47.392 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:47.395 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:47.397 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:48:47.400 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-23 11:48:48.855 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,2016-03-23 11:48:48.855 ThaliTest[2076:3553294] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 11:48:48.858 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:48.861 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:48.862 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:48.862 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-23 11:48:49.518 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:49.519 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:4
,2016-03-23 11:48:49.520 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:48:49.520 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:4
,2016-03-23 11:48:49.521 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:48:49.524 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
2016-03-23 11:48:49.524 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
2016-03-23 11:48:49.525 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:48:49.525 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-23 11:48:49.788 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:48:49.791 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:49.793 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:49.794 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:49.795 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-23 11:48:50.316 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:50.317 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:5
,2016-03-23 11:48:50.318 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,2016-03-23 11:48:50.319 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:5
2016-03-23 11:48:50.320 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
ok 147 Can call startUpdateAdv,ertisingAndListening without error
2016-03-23 11:48:50.324 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:48:50.326 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
2016-03-23 11:48:50.326 ThaliTest[2076:355329,4] multipeer manager: stop client timer
2016-03-23 11:48:50.326 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:6
2016-03-23 11:48:50.327 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
201,6-03-23 11:48:50.328 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:6
2016-03-23 11:48:50.328 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 148 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,2016-03-23 11:48:50.526 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:48:50.529 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:50.532 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:50.532 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:50.533 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:48:50.534 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-23 11:48:50.936 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:48:50.937 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:7
,2016-03-23 11:48:50.938 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:48:50.939 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:7
2016-03-23 11:48:50.939 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-23 11:48:50.942 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 11:48:50.945 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 152 Can call startListeningForAdvertisements without error
,2016-03-23 11:48:52.087 ThaliTest[2076:3553059] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:7
,ok 153 peers must be an array
,ok 154 peers must not be zero-length
,ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-23 11:48:53.102 ThaliTest[2076:3553059] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:7
,2016-03-23 11:48:54.582 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:48:54.584 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:48:54.586 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:48:54.587 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:48:54.588 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:48:54.588 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-23 11:49:25.408 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:49:25.409 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
,2016-03-23 11:49:25.410 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:49:25.410 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8
2016-03-23 11:49:25.411 ,ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 161 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:49:25.413 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-23 11:49:25.416 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-23 11:49:26.187 ThaliTest[2076:3553059] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"71AA62C9-76E6-4355-A877-ED5FEA587FD9:8","pleaseConnect":0}]
,2016-03-23 11:49:26.194 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:26.194 ThaliTest[2076:3553294] client session: connect
,2016-03-23 11:49:26.195 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:49:26.740 ThaliTest[2076:3553059] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8","pleaseConnect":0}]
,2016-03-23 11:49:31.248 ThaliTest[2076:3553770] client session: p2p link connected
,2016-03-23 11:49:31.253 ThaliTest[2076:3553770] client session: stateChange:1->2 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:49:31.254 ThaliTest[2076:3553770] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:49:31.254 ThaliTest[2076:3553770] jxcore: connect: success
,INFO testThaliMobileNative: 
,ok 163 Must have listeningPort
,ok 164 listeningPort must be a number
,ok 165 Connection must have clientPort
,ok 166 clientPort must be a number
,ok 167 Connection must have serverPort
,ok 168 serverPort must be a number
,ok 169 forward connection must have clientPort == 0
,ok 170 forward connection must have serverPort == 0
,# teardown
,2016-03-23 11:49:45.412 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:49:45.433 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:49:45.434 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:05.411 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:50:05.432 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:50:05.434 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:50:25.412 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:50:25.432 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:50:25.433 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:50:45.412 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:50:45.435 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:50:45.436 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:05.412 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:51:05.434 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
2016-03-23 11:51:05.435 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:25.286 ThaliTest[2076:3555089] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:25.286 ThaliTest[2076:3555089] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:25.2,87 ThaliTest[2076:3555089] client session: disconnect
2016-03-23 11:51:25.287 ThaliTest[2076:3555089] client session: stateChange:2->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:25.412 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:51:25.735 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:51:25.737 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 171 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:51:25.739 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:51:25.740 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:51:25.741 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:51:25.741 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can shift large amounts of data
,2016-03-23 11:51:27.649 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:51:27.649 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
,2016-03-23 11:51:27.651 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:51:27.651 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9
2016-03-23 11:51:27.652 ,ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 173 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 11:51:27.654 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-23 11:51:27.657 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdv,ertisements without error
,2016-03-23 11:51:28.519 ThaliTest[2076:3553059] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:28.521 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:28.522 ThaliTest[2076:3,553294] client session: connect
2016-03-23 11:51:28.522 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:28.547 ThaliTest[2076:3553059] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:8
,2016-03-23 11:51:29.071 ThaliTest[2076:3555091] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:29.072 ThaliTest[2076:3555091] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:29.073 ThaliTest[2076:3555091] client session: disconnect
,2016-03-23 11:51:29.073 ThaliTest[2076:3555091] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:29.075 ThaliTest[2076:3555091] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:29.075 ThaliTest[2076:3555091] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 11:51:30.534 ThaliTest[2076:3553059] multipeer session: reset timer
,2016-03-23 11:51:30.534 ThaliTest[2076:3553059] server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9 != D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8)
,2016-03-23 11:51:32.086 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:32.087 ThaliTest[2076:3553294] client session: connect
2016-03-23 11:51:32.088 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:33.221 ThaliTest[2076:3555089] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:33.221 ThaliTest[2076:3555089] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:33.222 ThaliTest[2076:3555089] client session: disconnect
2016-03-23 11:51:33.223 ThaliTest[2076:3555089] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:33.224 ThaliTest[2076:3555089] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:33.224 ThaliTest[2076:3555089] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 11:51:36.228 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:36.229 ThaliTest[2076:3553294] client session: connect
2016-03-23 11:51:36.229 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:36.808 ThaliTest[2076:3555104] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:36.809 ThaliTest[2076:3555104] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:36.810 ThaliTest[2076:3555104] client session: disconnect
2016-03-23 11:51:36.810 ThaliTest[2076:3555104] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:36.811 ThaliTest[2076:3555104] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:36.811 ThaliTest[2076:3555104] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 11:51:39.822 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:39.822 ThaliTest[2076:3553294] client session: connect
,2016-03-23 11:51:39.823 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:40.011 ThaliTest[2076:3555089] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:40.012 ThaliTest[2076:3555089] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:40.0,12 ThaliTest[2076:3555089] client session: disconnect
2016-03-23 11:51:40.012 ThaliTest[2076:3555089] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:40.013 ThaliTest[2076:3555089] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:40.015 ThaliTest[2076:3555089] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 11:51:41.073 ThaliTest[2076:3553059] multipeer session: reset timer
,2016-03-23 11:51:41.074 ThaliTest[2076:3553059] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:51:41.074 ThaliTest[2076:3553059] server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9 != D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8)
,2016-03-23 11:51:43.029 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:43.029 ThaliTest[2076:3553294] client session: connect
,2016-03-23 11:51:43.030 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:43.154 ThaliTest[2076:3555104] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:43.155 ThaliTest[2076:3555104] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:43.155 ThaliTest[2076:3555104] client session: disconnect
2016-03-23 11:51:43.155 ThaliTest[2076:3555104] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:43.156 ThaliTest[2076:3555104] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:43.157 ThaliTest[2076:3555104] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 11:51:46.163 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:46.164 ThaliTest[2076:3553294] client session: connect
,2016-03-23 11:51:46.164 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:46.271 ThaliTest[2076:3555104] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:46.273 ThaliTest[2076:3555104] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:46.273 ThaliTest[2076:3555104] client session: disconnect
2016-03-23 11:51:46.274 ThaliTest[2076:3555104] client session:, stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
2016-03-23 11:51:46.274 ThaliTest[2076:3555104] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:46.275 ThaliTest[2076:3555104] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 11:51:47.653 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:51:47.672 ThaliTest[2076:3553059] client: found updated peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:51:47.673 ThaliTest[2076:3553059] client: found updated peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:49.284 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:49.285 ThaliTest[2076:3553294] client session: connect
,2016-03-23 11:51:49.285 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:49.506 ThaliTest[2076:3555230] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:51:49.507 ThaliTest[2076:3555230] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:49.507 ThaliTest[2076:3555230] client session: disconnect
2016-03-23 11:51:49.507 ThaliTest[2076:3555230] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:49.509 ThaliTest[2076:3555230] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:49.509 ThaliTest[2076:3555230] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 11:51:52.523 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:52.524 ThaliTest[2076:3553294] client session: connect
2016-03-23 11:51:52.525 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:52.674 ThaliTest[2076:3555231] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:51:52.674 ThaliTest[2076:3555231] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:52.676 ThaliTest[2076:3555231] client session: disconnect
2016-03-23 11:51:52.676 ThaliTest[2076:3555231] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:51:52.677 ThaliTest[2076:3555231] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:52.677 ThaliTest[2076:3555231] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 11:51:54.294 ThaliTest[2076:3553059] multipeer session: reset timer
,2016-03-23 11:51:54.295 ThaliTest[2076:3553059] server: disconnecting to refresh session (53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0)
2016-03-23 11:51:54.295 ThaliTest[2076:3553059] server: rejecting invitation from 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0 due to previous generation (D95DAC2A-FB09-4A72-B9F2-B5180B076E64:9 != D95DAC2A-FB09-4A72-B9F2-B5180B076E64:8)
,2016-03-23 11:51:55.682 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:55.683 ThaliTest[2076:3553294] client session: connect
,2016-03-23 11:51:55.684 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:55.812 ThaliTest[2076:3555230] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:51:55.813 ThaliTest[2076:3555230] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:55.814 ThaliTest[2076:3555230] client session: disconnect
2016-03-23 11:51:55.815 ThaliTest[2076:3555230] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:55.816 ThaliTest[2076:3555230] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:55.816 ThaliTest[2076:3555230] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 11:51:58.824 ThaliTest[2076:3553294] jxcore: connect 71AA62C9-76E6-4355-A877-ED5FEA587FD9:8
,2016-03-23 11:51:58.824 ThaliTest[2076:3553294] client session: connect
2016-03-23 11:51:58.825 ThaliTest[2076:3553294] client session: stateChange:0->1 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:58.989 ThaliTest[2076:3555230] client session: not connected 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:51:58.990 ThaliTest[2076:3555230] client session: onLinkFailure: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
2016-03-23 11:51:58.990 ThaliTest[2076:3555230] client session: disconnect
,2016-03-23 11:51:58.990 ThaliTest[2076:3555230] client session: stateChange:1->0 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:51:58.991 ThaliTest[2076:3555230] client session: fireConnectCallback: 71AA62C9-76E6-4355-A877-ED5FEA587FD9
,2016-03-23 11:51:58.993 ThaliTest[2076:3555230] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 175 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 11:52:07.652 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:52:07.666 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:52:07.666 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:27.653 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:52:27.667 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
2016-03-23 11:52:27.668 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:52:34.973 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 11:52:34.975 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 176 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 11:52:34.977 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:34.978 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:34.979 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:52:34.980 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 177 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-23 11:52:36.796 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:36.797 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:36.799 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:36.802 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 178 specific error should be returned
,# teardown
,# setup
,2016-03-23 11:52:42.762 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:42.763 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:42.764 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:42.768 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 179 specific error should be returned
,# teardown
,# setup
,2016-03-23 11:52:43.634 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:43.635 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:43.636 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:43.639 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51507
,2016-03-23 11:52:43.803 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:43.806 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 180 no errors
,2016-03-23 11:52:43.810 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:43.812 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 181 still no errors
,# teardown
,2016-03-23 11:52:43.940 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:43.940 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:43.941 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:43.942 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:43.944 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:44.184 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:44.184 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:44.185 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:44.188 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51509
,2016-03-23 11:52:44.391 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:52:44.393 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:44.398 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 182 no errors
,2016-03-23 11:52:44.402 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 11:52:44.405 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,ok 183 still no errors
,# teardown
,2016-03-23 11:52:44.571 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:44.572 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:44.572 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:44.574 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
2016-03-23 11:52:44.574 ThaliTest[2076:3553294] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:44.577 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:44.708 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:44.709 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:44.710 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:44.713 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51511
,2016-03-23 11:52:44.863 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:52:44.863 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:10
,2016-03-23 11:52:44.865 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:52:44.865 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:10
2016-03-23 11:52:44.866 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,ok 184 no errors
,2016-03-23 11:52:44.870 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
2016-03-23 11:52:44.870 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
2016-03-23 11:52:44.870 ThaliTest[2076:3553294] multipeer manager: stop client ti,mer
2016-03-23 11:52:44.871 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:11
2016-03-23 11:52:44.872 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:52:44.872 ThaliTest[2076,:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:11
2016-03-23 11:52:44.872 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
ok 185 still no errors
,# teardown
,2016-03-23 11:52:45.140 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
2016-03-23 11:52:45.140 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:45.141 ThaliTest[2076:3553294] multipeer manager: stop client timer
2016-03-23 11:52:45.141 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:45.142 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:45.144 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:45.322 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:45.324 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:45.325 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:45.327 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51515
,2016-03-23 11:52:48.145 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:48.145 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:48.146 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 186 no errors
,2016-03-23 11:52:48.149 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:48.149 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
2016-03-23 11:52:48.150 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,ok 187 still no errors
,# teardown
,2016-03-23 11:52:48.822 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:48.823 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:48.824 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:48.825 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:48.827 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:52:50.024 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:50.025 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:50.026 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:50.029 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. can get the network status before starting
,ok 188 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-23 11:52:50.810 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:50.811 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:50.813 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:50.817 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 189 specific error expected
,# teardown
,# setup
,2016-03-23 11:52:51.188 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:51.189 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:51.190 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:51.194 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51517
,2016-03-23 11:52:51.465 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:52:51.466 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 11:52:51.470 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:52:51.472 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:52:51.473 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:12
,2016-03-23 11:52:51.474 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:12
2016-03-23 11:52:51.474 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 190 connection to servers manager should succeed after starting
,ok 191 connection to router server should succeed after starting
,2016-03-23 11:52:51.522 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:51.522 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:51.523 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
2016-03-23 11:52:51.524 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
2016-03-23 11:52:51.524 ThaliTest[2076:3553294] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:51.529 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 192 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 193 connection to servers manager should fail after stopping
,ok 194 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-23 11:52:51.895 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:51.897 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:51.898 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:51.901 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. make sure terminateConnection is properly hooked up
,ok 195 called with right arguments
,# teardown
,# setup
,2016-03-23 11:52:52.483 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:52.484 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:52.486 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:52.488 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. make sure terminateListener is properly hooked up
,ok 196 called with right arguments
,# teardown
,# setup
,2016-03-23 11:52:57.084 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:57.085 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:57.086 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:57.089 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure we actually call kill connections properly
,2016-03-23 11:52:59.040 ThaliTest[2076:3553294] jxcore: killConnections
2016-03-23 11:52:59.040 ThaliTest[2076:3553294] jxcore: killConnections: badParam
,not ok 197 should not fail on iOS
,  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-23 11:52:59.424 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:59.425 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:59.426 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:59.429 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51524
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51523,"error":{}}
,2016-03-23 11:52:59.558 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:52:59.559 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:52:59.559 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:52:59.561 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:52:59.563 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,ok 198 failure reason is as expected
,ok 199 error description is as expected
,ok 200 must be stopped
,# teardown
,# setup
,2016-03-23 11:52:59.971 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:52:59.972 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:52:59.973 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:52:59.977 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51526
,ok 201 peerIdentifier matches
,ok 202 error description matches
,# teardown
,2016-03-23 11:53:00.350 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
2016-03-23 11:53:00.350 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
2016-03-23 11:53:00.350 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:53:00.352 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 11:53:00.354 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 11:53:00.468 ThaliTest[2076:3553294] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 11:53:00.469 ThaliTest[2076:3553294] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 11:53:00.470 ThaliTest[2076:3553294] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 11:53:00.473 ThaliTest[2076:3553294] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51528
,2016-03-23 11:53:00.626 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements
,2016-03-23 11:53:00.626 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 203 discoveryActive matches
,ok 204 advertisingActive matches
,2016-03-23 11:53:00.634 ThaliTest[2076:3553294] jxcore: startListeningForAdvertisements: success
,2016-03-23 11:53:00.636 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening
,2016-03-23 11:53:00.636 ThaliTest[2076:3553294] THEMultipeerManager stopping peer
,2016-03-23 11:53:00.637 ThaliTest[2076:3553294] jxcore: stopAdvertisingAndListening: success
,2016-03-23 11:53:00.638 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements
,2016-03-23 11:53:00.638 ThaliTest[2076:3553294] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 205 discoveryActive matches
,ok 206 advertisingActive matches
,2016-03-23 11:53:00.645 ThaliTest[2076:3553294] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51530
,2016-03-23 11:53:00.659 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 11:53:00.660 ThaliTest[2076:3553294] server: starting D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
,2016-03-23 11:53:00.661 ThaliTest[2076:3553294] multipeer manager: start client restart timer: 0x14dd3e90
2016-03-23 11:53:00.661 ThaliTest[2076:3553294] THEMultipeerManager initialized peer D95DAC2A-FB09-4A72-B9F2-B5180B076E64:13
2016-03-23 11:53:00.662 ThaliTest[2076:3553294] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-23 11:53:01.781 ThaliTest[2076:3553059] client: found new peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:9
,2016-03-23 11:53:01.790 ThaliTest[2076:3553059] client: found new peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:9
,2016-03-23 11:53:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:53:20.677 ThaliTest[2076:3553059] client: found updated peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:53:20.678 ThaliTest[2076:3553059] client: found updated peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:53:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:53:40.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:53:40.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:54:00.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:54:00.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:54:00.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:54:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:54:20.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:54:20.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:54:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:54:40.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:54:40.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:55:00.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:55:00.675 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:55:00.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:55:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:55:20.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:55:20.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:55:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:55:40.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:55:40.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:56:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:56:00.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:56:00.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:56:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:56:20.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:56:20.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:56:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:56:40.675 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:56:40.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:57:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:57:00.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:57:00.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:57:20.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:57:20.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:57:20.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:57:40.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:57:40.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:57:40.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:58:00.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:58:00.675 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:58:00.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 11:58:20.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:58:20.675 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:58:20.675 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:58:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:58:40.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:58:40.679 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:59:00.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:59:00.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:59:00.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:59:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:59:20.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 11:59:20.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 11:59:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 11:59:40.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 11:59:40.679 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:00:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:00:00.675 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:00:00.675 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:00:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:00:20.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:00:20.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:00:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:00:40.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:00:40.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:01:00.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:01:00.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:01:00.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:01:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:01:21.278 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:01:21.279 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:01:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:01:40.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:01:40.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:02:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:02:00.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:02:00.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:02:20.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:02:20.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:02:20.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:02:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:02:40.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:02:40.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:03:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:03:00.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:03:00.679 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:03:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:03:20.677 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:03:20.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:03:40.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:03:40.675 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:03:40.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:04:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:04:00.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:04:00.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:04:20.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:04:20.675 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:04:20.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:04:40.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:04:40.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:04:40.679 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:05:00.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:05:00.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:05:00.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:05:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:05:20.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:05:20.676 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:05:40.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:05:40.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:05:40.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:06:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:06:00.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:06:00.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
,2016-03-23 12:06:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:06:20.676 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:06:20.677 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:06:40.662 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:06:40.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:06:40.679 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:07:00.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:07:00.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13
2016-03-23 12:07:00.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
,2016-03-23 12:07:20.663 ThaliTest[2076:3553059] multipeer manager: restart client
,2016-03-23 12:07:20.678 ThaliTest[2076:3553059] client: found existing peer: 71AA62C9-76E6-4355-A877-ED5FEA587FD9:13
2016-03-23 12:07:20.678 ThaliTest[2076:3553059] client: found existing peer: 53D90CC2-4DC8-4E53-BC37-B4697E6BF5F0:13

```
