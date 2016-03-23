#### Test 63848581b00dd7c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/42612768-A071-42BD-A315-492D786224DE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/42612768-A071-42BD-A315-492D786224DE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63848581b00dd7c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55248"
,(lldb)     command script import "/tmp/42612768-A071-42BD-A315-492D786224DE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-23 13:03:42.160 ThaliTest[2055:3576444] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CF69959F-BE99-4BC8-8A20-BF3198306665/Library/Cookies/Cookies.binarycookies
,2016-03-23 13:03:42.525 ThaliTest[2055:3576444] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-23 13:03:42.526 ThaliTest[2055:3576444] Multi-tasking -> Device: YES, App: YES
,2016-03-23 13:03:42.546 ThaliTest[2055:3576444] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-23 13:03:44.477 ThaliTest[2055:3576444] Using UIWebView
,2016-03-23 13:03:44.485 ThaliTest[2055:3576444] [CDVTimer][handleopenurl] 0.648975ms
,2016-03-23 13:03:44.494 ThaliTest[2055:3576444] [CDVTimer][intentandnavigationfilter] 8.049011ms
2016-03-23 13:03:44.495 ThaliTest[2055:3576444] [CDVTimer][gesturehandler] 0.442028ms
2016-03-23 13:03:44.495 ThaliTest[2055:3576444] [CDVTimer][TotalPluginS,tartup] 11.088014ms
,2016-03-23 13:03:51.325 ThaliTest[2055:3576444] Resetting plugins due to page load.
,2016-03-23 13:03:54.798 ThaliTest[2055:3576444] Finished load of: file:///var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/index.html
,2016-03-23 13:03:55.043 ThaliTest[2055:3576444] JXcore Cordova plugin initializing
,2016-03-23 13:03:55.045 ThaliTest[2055:3576654] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-23 13:04:03.665 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:04:03.666 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:04:03.666 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:04:03.668 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C30BEE0F-60AC-41BF-B4E8-156C1A67D007/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-23 13:04:10.629 ThaliTest[2055:3576444] THREAD WARNING: ['JXcore'] took '6591.532959' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51269
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51271
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
,DEBUG createNativeListener: listening 51274
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
,DEBUG createNativeListener: listening 51278
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
,DEBUG createNativeListener: listening 51283
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
,DEBUG createNativeListener: listening 51287
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
,DEBUG createNativeListener: listening 51291
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
,DEBUG createNativeListener: listening 51295
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
,DEBUG createNativeListener: listening 51299
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
,DEBUG createNativeListener: listening 51351
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
,DEBUG createNativeListener: listening 51355
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
,DEBUG createNativeListener: listening 51367
,2016-03-23 13:06:23.005 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:23.009 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-23 13:06:23.016 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:23.019 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-23 13:06:23.153 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:23.155 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
,2016-03-23 13:06:23.156 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:23.159 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:23.162 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51369
,2016-03-23 13:06:23.566 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,2016-03-23 13:06:23.570 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:23.573 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-23 13:06:23.605 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:23.609 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-23 13:06:26.052 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:26.052 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
,2016-03-23 13:06:26.053 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:06:26.055 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
2016-03-23 13:06:26.055 ThaliTest[2055:3576654] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:26.058 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51371
,2016-03-23 13:06:28.229 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:28.230 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:1
2016-03-23 13:06:28.231 ThaliTest[2055:3576654] multipeer m,anager: start client restart timer: 0x156d10d0
2016-03-23 13:06:28.232 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:1
2016-03-23 13:06:28.233 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-23 13:06:28.271 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:28.273 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
,2016-03-23 13:06:28.277 ThaliTest[2055:3576654] multipeer manager: stop client timer
,2016-03-23 13:06:28.283 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:2
,2016-03-23 13:06:28.292 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
,2016-03-23 13:06:28.302 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:2
,2016-03-23 13:06:28.304 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-23 13:06:28.781 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:28.782 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:28.783 ThaliTest[2055:3576654] multipeer manager: stop client timer
2016-03-23 13:06:28.784 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: su,ccess
2016-03-23 13:06:28.784 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:28.786 ThaliTest[205,5:3576654] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51376
,2016-03-23 13:06:31.914 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:31.915 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:31.915 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,2016-03-23 13:06:31.922 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:31.923 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:31.923 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-23 13:06:32.376 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:32.377 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:32.377 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:32.381 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:06:32.384 ThaliTest[2055:35766,54] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51378
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-23 13:06:34.825 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:34.826 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:34.826 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:06:34.827 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:34.831 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51380
,2016-03-23 13:06:35.208 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
2016-03-23 13:06:35.208 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:35.212 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,2016-03-23 13:06:35.270 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:06:35.271 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:3
,2016-03-23 13:06:35.273 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:3
,2016-03-23 13:06:35.276 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-23 13:06:35.610 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:35.612 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
,2016-03-23 13:06:35.615 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,2016-03-23 13:06:35.617 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,2016-03-23 13:06:35.619 ThaliTest[2055:3576654] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:35.627 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
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
,2016-03-23 13:06:46.477 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
2016-03-23 13:06:46.478 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:46.483 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAd,vertisements without error
2016-03-23 13:06:46.489 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,2016-03-23 13:06:46.490 ThaliTest[2055:3576654] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:46.498 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-23 13:06:46.739 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:46.741 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:46.745 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:46.745 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:46.746 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-23 13:06:47.788 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
2016-03-23 13:06:47.788 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-23 13:06:47.791 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:47.795 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:06:47.801 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-23 13:06:48.440 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
2016-03-23 13:06:48.441 ThaliTest[2055:3576654] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:48.443 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:48.453 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:48.454 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
,2016-03-23 13:06:48.456 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-23 13:06:48.923 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:48.923 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:4
2016-03-23 13:06:48.924 ThaliTest[2055:3576654] multipeer m,anager: start client restart timer: 0x156d10d0
2016-03-23 13:06:48.925 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:4
2016-03-23 13:06:48.925 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,ok 143 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:06:48.929 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
,2016-03-23 13:06:48.930 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:48.931 ThaliTest[2055:3576654] multipeer manager: stop client timer
2016-03-23 13:06:48.931 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: su,ccess
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-23 13:06:49.571 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:06:49.574 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:49.577 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:49.578 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:49.578 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: suc,cess
ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-23 13:06:50.109 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:50.110 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:5
2016-03-23 13:06:50.111 ThaliTest[2055:3576654] multipeer m,anager: start client restart timer: 0x156d10d0
2016-03-23 13:06:50.111 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:5
2016-03-23 13:06:50.111 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-23 13:06:50.114 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:50.115 ThaliTest[2055:3576654] THEMultipeerManager stopping pee,r
2016-03-23 13:06:50.115 ThaliTest[2055:3576654] multipeer manager: stop client timer
2016-03-23 13:06:50.115 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:6
2016-03-23 13:06:50.116 ThaliTest[2055:3576654] multipeer mana,ger: start client restart timer: 0x156d10d0
2016-03-23 13:06:50.130 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:6
2016-03-23 13:06:50.131 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListe,ning: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-23 13:06:50.305 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:06:50.308 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:50.310 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:50.311 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:50.311 ThaliTest[2055:3576654] multipeer manager: stop client timer
20,16-03-23 13:06:50.312 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-23 13:06:50.712 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:50.712 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
2016-03-23 13:06:50.713 ThaliTest[2055:3576654] multipeer m,anager: start client restart timer: 0x156d10d0
2016-03-23 13:06:50.714 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7
2016-03-23 13:06:50.714 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-23 13:06:50.721 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 13:06:50.724 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:51.603 ThaliTest[2055:3576444] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,ok 153 peers must be an array
ok 154 peers must not be zero-length
ok 155 peer must have peerIdentifier
ok 156 peerIdentifier must be a string
ok 157 peer must have peerAvailable
ok 158 peer must have pleaseConnect
,# teardown
,2016-03-23 13:06:51.810 ThaliTest[2055:3576444] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:06:51.969 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:06:51.973 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:06:51.977 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:06:51.977 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:06:51.978 ThaliTest[2055:3576654] multipeer manager: stop client timer
20,16-03-23 13:06:51.978 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-23 13:06:52.714 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:06:52.715 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
,2016-03-23 13:06:52.715 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
2016-03-23 13:06:52.717 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8
2016-03-23 13:06:52.718 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,ok 161 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:06:52.721 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-23 13:06:52.725 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-23 13:06:53.586 ThaliTest[2055:3576444] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:06:53.590 ThaliTest[2055:3576444] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F676A619-7581-458A-A82D-21194588BD7A:7","pleaseConnect":0}]
2016-03-23 13:06:53.593 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 1,3:06:53.594 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:06:53.595 ThaliTest[2055:3576654] client session: reverseConnect
2016-03-23 13:06:53.595 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-211945,88BD7A:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7","pleaseConnect":0}]
,2016-03-23 13:06:53.683 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:06:53.684 ThaliTest[2055:3576444] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:06:54.203 ThaliTest[2055:3576985] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:06:54.203 ThaliTest[2055:3576985] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:06:54.2,03 ThaliTest[2055:3576985] client session: disconnect
,2016-03-23 13:06:54.204 ThaliTest[2055:3576985] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:06:54.207 ThaliTest[2055:3576985] client session: no connect callback (server initiated)
,2016-03-23 13:06:56.893 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:06:56.894 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:06:56.894 ThaliTest[2055:3576444], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:00.106 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:00.106 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
,2016-03-23 13:07:00.107 ThaliTest[2055:3576444] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:03.583 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:03.583 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:07:03.584 ThaliTest[2055:3576444], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:03.595 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 13:07:06.605 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:06.606 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:07:06.606 ThaliTest[2055:3576654] client session: reverseConn,ect
2016-03-23 13:07:06.606 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:06.719 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:06.719 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:07:06.720 ThaliTest[2055:3576444], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:07.208 ThaliTest[2055:3576985] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:07.210 ThaliTest[2055:3576985] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
,2016-03-23 13:07:07.211 ThaliTest[2055:3576985] client session: disconnect
2016-03-23 13:07:07.212 ThaliTest[2055:3576985] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:07.214 ThaliTest[2055:3576985] client session: no connect callback (server initiated)
,2016-03-23 13:07:09.937 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:09.938 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:07:09.938 ThaliTest[2055:3576444], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:12.718 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:07:12.752 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:12.752 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:07:13.471 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:13.472 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:07:13.472 ThaliTest[2055:3576444], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:16.606 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 13:07:16.686 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:16.687 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
,2016-03-23 13:07:16.689 ThaliTest[2055:3576444] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:19.621 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:19.622 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:07:19.622 ThaliTest[2055:3576654] client session: reverseConn,ect
2016-03-23 13:07:19.623 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:20.027 ThaliTest[2055:3577040] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:20.031 ThaliTest[2055:3577040] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
,2016-03-23 13:07:20.032 ThaliTest[2055:3577040] client session: disconnect
,2016-03-23 13:07:20.032 ThaliTest[2055:3577040] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:20.035 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:20.036 ThaliTest[2055:3577040] client session: no connect callback (server initiated)
,2016-03-23 13:07:20.036 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:07:20.037 ThaliTest[2055:3576444] server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to p,revious generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:23.499 ThaliTest[2055:3576444] multipeer session: reset timer
2016-03-23 13:07:23.500 ThaliTest[2055:3576444] server: disconnecting to refresh session (F676A619-7581-458A-A82D-21194588BD7A)
2016-03-23 13:07:23.500 ThaliTest[2055:3576444], server: rejecting invitation from F676A619-7581-458A-A82D-21194588BD7A due to previous generation (30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:8 != 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:7)
,2016-03-23 13:07:29.623 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 13:07:32.632 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:32.632 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:07:32.633 ThaliTest[2055:3576654] client session: reverseConn,ect
2016-03-23 13:07:32.633 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:32.718 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:07:32.755 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:07:32.756 ThaliTest[2055:3576444] client: found updated peer: F676A619-7581-458A-A82D-21194588BD7A:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F676A619-7581-458A-A82D-21194588BD7A:8","pleaseConnect":0}]
,2016-03-23 13:07:42.634 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 13:07:45.649 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:45.650 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:45.650 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 13:07:48.669 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:48.670 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:48.670 ThaliTest[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 13:07:51.691 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:51.692 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:7
,2016-03-23 13:07:51.696 ThaliTest[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 13:07:52.719 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:07:52.751 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:07:52.754 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:07:54.719 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:54.720 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:54.720 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 13:07:57.742 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:57.743 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:07:57.743 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 13:08:00.754 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:08:00.755 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:7
2016-03-23 13:08:00.756 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 13:08:01.015 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:08:01.017 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:08:01.021 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:08:01.021 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:08:01.022 ThaliTest[2055:3576654] client session: disconnect
2016-03-23 1,3:08:01.022 ThaliTest[2055:3576654] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:01.023 ThaliTest[2055:3576654] multipeer manager: stop client timer
2016-03-23 13:08:01.024 ThaliTest[2055:3576654] jxcore: stopA,dvertisingAndListening: success
ok 165 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can shift large amounts of data
,2016-03-23 13:08:06.001 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:08:06.003 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:08:06.006 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
,2016-03-23 13:08:06.010 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:9
,2016-03-23 13:08:06.018 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,ok 166 Can call startUpdateAdvertisingAndListening without error
,2016-03-23 13:08:06.022 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-23 13:08:06.026 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 167 Can call startListeningForAdvertisements without error
,2016-03-23 13:08:06.863 ThaliTest[2055:3576444] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:06.866 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:06.868 ThaliTest[2055:3,576654] client: server will connect
,2016-03-23 13:08:06.869 ThaliTest[2055:3576654] client session: reverseConnect
,2016-03-23 13:08:06.873 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:07.405 ThaliTest[2055:3576444] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:8
,2016-03-23 13:08:08.702 ThaliTest[2055:3577128] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:08.703 ThaliTest[2055:3577128] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:08:08.7,03 ThaliTest[2055:3577128] client session: disconnect
2016-03-23 13:08:08.703 ThaliTest[2055:3577128] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:08.707 ThaliTest[2055:3577128] client session: no connect callback (server initiated)
,2016-03-23 13:08:16.869 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-23 13:08:19.885 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:19.885 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:08:19.886 ThaliTest[2055:3576654] client session: reverseConn,ect
2016-03-23 13:08:19.886 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:20.977 ThaliTest[2055:3577169] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:20.978 ThaliTest[2055:3577169] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:08:20.978 ThaliTest[2055:3577169] client session: disconnect
,2016-03-23 13:08:20.979 ThaliTest[2055:3577169] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:20.982 ThaliTest[2055:3577169] client session: no connect callback (server initiated)
,2016-03-23 13:08:26.010 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:08:26.039 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:26.047 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:08:29.887 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-23 13:08:32.898 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:32.898 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:08:32.899 ThaliTest[2055:3576654] client session: reverseConn,ect
2016-03-23 13:08:32.899 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:33.417 ThaliTest[2055:3577206] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:33.417 ThaliTest[2055:3577206] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
,2016-03-23 13:08:33.418 ThaliTest[2055:3577206] client session: disconnect
,2016-03-23 13:08:33.419 ThaliTest[2055:3577206] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:33.421 ThaliTest[2055:3577206] client session: no connect callback (server initiated)
,2016-03-23 13:08:42.900 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-23 13:08:45.907 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:45.907 ThaliTest[2055:3576654] client: server will connect
2016-03-23 13:08:45.908 ThaliTest[2055:3576654] client session: reverseConn,ect
2016-03-23 13:08:45.908 ThaliTest[2055:3576654] client session: stateChange:0->1 F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:08:46.010 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:08:46.033 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:46.034 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:08:55.909 ThaliTest[2055:3576444] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-23 13:08:58.923 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:58.924 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:08:58.924 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-23 13:09:01.939 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:01.940 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:01.940 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-23 13:09:04.952 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:04.953 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:04.953 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-23 13:09:06.010 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:09:06.041 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:09:06.042 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
,2016-03-23 13:09:07.963 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:07.964 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:07.964 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-23 13:09:10.978 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:10.979 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:10.979 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-23 13:09:13.990 ThaliTest[2055:3576654] jxcore: connect F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:13.991 ThaliTest[2055:3576654] client: already connect(ing/ed) to F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:13.991 Thali,Test[2055:3576654] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-23 13:09:18.917 ThaliTest[2055:3577206] client session: not connected F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:18.917 ThaliTest[2055:3577206] client session: onLinkFailure: F676A619-7581-458A-A82D-21194588BD7A
2016-03-23 13:09:18.9,18 ThaliTest[2055:3577206] client session: disconnect
2016-03-23 13:09:18.918 ThaliTest[2055:3577206] client session: stateChange:1->0 F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:18.919 ThaliTest[2055:3577206] client session: no connect callb,ack (server initiated)
,2016-03-23 13:09:26.010 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:09:26.039 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:26.040 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:09:46.010 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:09:46.042 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:8
2016-03-23 13:09:46.043 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:9
,2016-03-23 13:10:06.010 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:10:06.042 ThaliTest[2055:3576444] client: found updated peer: F676A619-7581-458A-A82D-21194588BD7A:9
2016-03-23 13:10:06.043 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:10:14.193 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-23 13:10:14.196 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-23 13:10:14.200 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:14.200 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:14.201 ThaliTest[2055:3576654] multipeer manager: stop client timer
20,16-03-23 13:10:14.201 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-23 13:10:18.343 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:18.344 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:18.344 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:18.349 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-23 13:10:18.972 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:18.973 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:18.974 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:18.978 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-23 13:10:20.710 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:20.711 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:20.712 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:20.716 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51408
,2016-03-23 13:10:21.035 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:21.037 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-23 13:10:21.042 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:21.044 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-23 13:10:21.444 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:21.444 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:21.445 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:10:21.445 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:21.450 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:21.738 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:21.739 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:21.739 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:21.743 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51410
,2016-03-23 13:10:22.016 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,2016-03-23 13:10:22.018 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:10:22.033 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 175 no errors
,2016-03-23 13:10:22.040 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:10:22.045 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-23 13:10:22.405 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:22.406 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:22.406 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:22.407 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
2016-03-23 13:10:22.408 ThaliTest[2055:3576654] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:22.417 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:22.569 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:22.570 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:22.571 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:22.575 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51412
,2016-03-23 13:10:22.842 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:10:22.843 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:10
2016-03-23 13:10:22.844 ThaliTest[2055:3576654] multipeer ,manager: start client restart timer: 0x156d10d0
2016-03-23 13:10:22.844 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:10
2016-03-23 13:10:22.845 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAnd,Listening: success
,ok 177 no errors
,2016-03-23 13:10:22.849 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:10:22.850 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:22.850 ThaliTest[2055:3576654] multipeer manager: stop client ti,mer
2016-03-23 13:10:22.850 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:11
2016-03-23 13:10:22.851 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
2016-03-23 13:10:22.852 ThaliTest[2055,:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:11
2016-03-23 13:10:22.852 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
ok 178 still no errors
# teardown
,2016-03-23 13:10:23.013 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:23.013 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:23.014 ThaliTest[2055:3576654] multipeer manager: stop client timer
20,16-03-23 13:10:23.014 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:10:23.015 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:23.020 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:23.569 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:23.571 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:23.572 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:23.579 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 45. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51416
,2016-03-23 13:10:24.495 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:24.496 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:24.496 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
ok 179 no errors
,2016-03-23 13:10:24.499 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
,2016-03-23 13:10:24.500 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
,2016-03-23 13:10:24.500 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
,ok 180 still no errors
,# teardown
,2016-03-23 13:10:24.861 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:24.862 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:24.862 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:10:24.863 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:24.867 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:25.045 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:25.046 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:25.047 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:25.050 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 46. can get the network status before starting
,ok 181 network status should have certain non-empty properties
,# teardown
,# setup
,2016-03-23 13:10:28.655 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-23 13:10:28.657 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-23 13:10:28.660 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:28.664 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 47. error returned with bad router
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 182 specific error expected
,# teardown
,# setup
,2016-03-23 13:10:30.117 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:30.118 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:30.119 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:30.122 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 48. all services are stopped when we call stop
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51418
,2016-03-23 13:10:30.393 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
2016-03-23 13:10:30.393 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-23 13:10:30.395 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
2016-03-23 13:10:30.405 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
2016-03-23 13:10:30.406 ThaliTest[2055:3576654] server: starting 3,0729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:12
2016-03-23 13:10:30.407 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:12
2016-03-23 13:10:30.408 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening,: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 183 connection to servers manager should succeed after starting
,ok 184 connection to router server should succeed after starting
,2016-03-23 13:10:30.469 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:30.470 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:30.470 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:30.471 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
2016-03-23 13:10:30.472 ThaliTest[2055:3576654] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-23 13:10:30.478 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 185 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 186 connection to servers manager should fail after stopping
,ok 187 connection to router server should fail after stopping
,# teardown
,# setup
,2016-03-23 13:10:33.258 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:33.259 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:33.259 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-23 13:10:33.262 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 49. make sure terminateConnection is properly hooked up
,ok 188 called with right arguments
,# teardown
,# setup
,2016-03-23 13:10:37.769 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:37.770 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:37.771 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:37.775 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 50. make sure terminateListener is properly hooked up
,ok 189 called with right arguments
,# teardown
,# setup
,2016-03-23 13:10:38.248 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:38.249 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:38.250 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:38.254 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 51. make sure we actually call kill connections properly
,2016-03-23 13:10:38.383 ThaliTest[2055:3576654] jxcore: killConnections
2016-03-23 13:10:38.383 ThaliTest[2055:3576654] jxcore: killConnections: badParam
,not ok 190 should not fail on iOS
  ---
,    operator: fail
,  ...
,# teardown
,# setup
,2016-03-23 13:10:38.721 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:38.722 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:38.723 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:38.727 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51425
,INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":51424,"error":{}}
,2016-03-23 13:10:38.882 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:38.882 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:38.883 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:38.883 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:38.886 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,ok 191 failure reason is as expected
,ok 192 error description is as expected
,ok 193 must be stopped
,# teardown
,# setup
,2016-03-23 13:10:39.295 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:39.296 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:39.297 ThaliTest[2055:3,576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:39.302 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 53. We repeat failedConnection event when we get it from thaliTcpServersManager
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51427
,ok 194 peerIdentifier matches
,ok 195 error description matches
,# teardown
,2016-03-23 13:10:39.550 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03-23 13:10:39.551 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:39.551 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-23 13:10:39.552 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-23 13:10:39.556 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-23 13:10:39.659 ThaliTest[2055:3576654] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-23 13:10:39.660 ThaliTest[2055:3576654] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-23 13:10:39.661 ThaliTest[2055:3576654] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-23 13:10:39.665 ThaliTest[2055:3576654] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 54. we successfully receive and replay discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51429
,2016-03-23 13:10:39.815 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements
2016-03-23 13:10:39.816 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,ok 196 discoveryActive matches
ok 197 advertisingActive matches
2016-03-23 13:10:39.823 ThaliTest[2055:3576654] jxcore: startListeningForAdvertisements: success
2016-03-23 13:10:39.824 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening
2016-03,-23 13:10:39.825 ThaliTest[2055:3576654] THEMultipeerManager stopping peer
2016-03-23 13:10:39.825 ThaliTest[2055:3576654] jxcore: stopAdvertisingAndListening: success
2016-03-23 13:10:39.826 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements,
2016-03-23 13:10:39.827 ThaliTest[2055:3576654] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,ok 198 discoveryActive matches
,ok 199 advertisingActive matches
2016-03-23 13:10:39.846 ThaliTest[2055:3576654] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51431
,2016-03-23 13:10:39.865 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening
,2016-03-23 13:10:39.867 ThaliTest[2055:3576654] server: starting 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:10:39.867 ThaliTest[2055:3576654] multipeer manager: start client restart timer: 0x156d10d0
,2016-03-23 13:10:39.868 ThaliTest[2055:3576654] THEMultipeerManager initialized peer 30729D1E-C4F7-4EC8-8D8E-99BBA3DE9B8D:13
2016-03-23 13:10:39.871 ThaliTest[2055:3576654] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-23 13:10:40.516 ThaliTest[2055:3576444] client: found new peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:10:40.549 ThaliTest[2055:3576444] client: found new peer: F676A619-7581-458A-A82D-21194588BD7A:9
,2016-03-23 13:10:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:10:59.900 ThaliTest[2055:3576444] client: found updated peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:10:59.903 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:11:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:11:19.895 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:11:19.908 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:11:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:11:39.897 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:11:39.909 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:11:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:11:59.900 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:11:59.900 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:12:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:12:19.895 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:12:19.907 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:12:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:12:39.901 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:12:39.904 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:12:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:12:59.893 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:12:59.908 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:13:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:13:19.902 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:13:19.905 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:13:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:13:39.907 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:13:39.909 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:13:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:13:59.902 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:13:59.907 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:14:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:14:19.901 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:14:19.902 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:14:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:14:39.899 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:14:39.900 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:14:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:14:59.897 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:14:59.899 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:15:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:15:19.899 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:15:19.902 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:15:39.868 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:15:39.894 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:15:39.908 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:15:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:15:59.896 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:15:59.909 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:16:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:16:19.894 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:16:19.907 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:16:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:16:39.895 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:16:39.909 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:16:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:16:59.904 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:16:59.906 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:17:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:17:19.903 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:17:19.905 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:17:39.868 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:17:39.903 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:17:39.906 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:17:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:17:59.893 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:17:59.906 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:18:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:18:19.901 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:18:19.902 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:18:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:18:39.906 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:18:39.909 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:18:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:18:59.904 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:18:59.905 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:19:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:19:19.901 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:19:19.902 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:19:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:19:39.901 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:19:39.906 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:19:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:19:59.900 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:19:59.905 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:20:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:20:19.893 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:20:19.908 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:20:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:20:39.894 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:20:39.910 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:20:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:20:59.897 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:20:59.911 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:21:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:21:19.901 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:21:19.902 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:21:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:21:39.902 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:21:39.905 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:21:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:21:59.905 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:21:59.908 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:22:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:22:19.900 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:22:19.903 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:22:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:22:39.899 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:22:39.902 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:22:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:22:59.895 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:22:59.912 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:23:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:23:19.902 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:23:19.904 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:23:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:23:39.894 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:23:39.906 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:23:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:23:59.897 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:23:59.898 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:13
,2016-03-23 13:24:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:24:19.899 ThaliTest[2055:3576444] client: found updated peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
2016-03-23 13:24:19.900 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
,2016-03-23 13:24:39.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:24:39.897 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:24:39.905 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:24:59.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:24:59.900 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:24:59.901 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7
,2016-03-23 13:25:19.869 ThaliTest[2055:3576444] multipeer manager: restart client
,2016-03-23 13:25:19.903 ThaliTest[2055:3576444] client: found existing peer: F676A619-7581-458A-A82D-21194588BD7A:13
2016-03-23 13:25:19.906 ThaliTest[2055:3576444] client: found existing peer: 6FD1548C-E6F2-4ACB-A3FC-EA8829744C6D:7

```
