#### Test 62548124d9c0fd9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/1167C4AE-9177-4EAA-96D5-8D73A1A50FEA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1167C4AE-9177-4EAA-96D5-8D73A1A50FEA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53102"
,(lldb)     command script import "/tmp/1167C4AE-9177-4EAA-96D5-8D73A1A50FEA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-19 12:51:30.989 ThaliTest[1791:2966105] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FDA709F4-90BB-4129-99DE-BE1774ABD94A/Library/Cookies/Cookies.binarycookies
,2016-03-19 12:51:31.459 ThaliTest[1791:2966105] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-19 12:51:31.461 ThaliTest[1791:2966105] Multi-tasking -> Device: YES, App: YES
,2016-03-19 12:51:31.490 ThaliTest[1791:2966105] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-19 12:51:33.476 ThaliTest[1791:2966105] Using UIWebView
,2016-03-19 12:51:33.484 ThaliTest[1791:2966105] [CDVTimer][handleopenurl] 0.476003ms
,2016-03-19 12:51:33.493 ThaliTest[1791:2966105] [CDVTimer][intentandnavigationfilter] 8.293986ms
2016-03-19 12:51:33.494 ThaliTest[1791:2966105] [CDVTimer][gesturehandler] 0.386953ms
2016-03-19 12:51:33.494 ThaliTest[1791:2966105] [CDVTimer][TotalPluginS,tartup] 11.045992ms
,2016-03-19 12:51:40.584 ThaliTest[1791:2966105] Resetting plugins due to page load.
,2016-03-19 12:51:44.490 ThaliTest[1791:2966105] Finished load of: file:///var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/index.html
,2016-03-19 12:51:44.734 ThaliTest[1791:2966105] JXcore Cordova plugin initializing
,2016-03-19 12:51:44.736 ThaliTest[1791:2966305] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-19 12:51:53.375 ThaliTest[1791:2966305] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-19 12:51:53.377 ThaliTest[1791:2966305] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 12:51:53.377 ThaliTest[1791:2966305] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 12:51:53.379 ThaliTest[1791:2966305] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/7CFD7A19-7671-4C64-A394-7F70271AC0B3/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-19 12:52:00.408 ThaliTest[1791:2966105] THREAD WARNING: ['JXcore'] took '6659.504883' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65257
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65259
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# setup
,# 3. emits routerPortConnectionFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65262
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# 4. native server connections all up
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65266
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
,# setup
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65271
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,DEBUG createNativeListener: mux close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65275
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
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65279
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,DEBUG createNativeListener: mux close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: incoming socket close
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65283
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
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65287
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
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65339
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
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65343
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
,# setup
,# 12. closeAll can close even when connections open
,# teardown
,ok 45 not possible to connect to the server anymore
,# setup
,# 13. closeAll with promise
,# teardown
,ok 46 not possible to connect to the server anymore
,# setup
,# 14. multiplex can send data
,# teardown
,ok 47 String should be length:200
,# setup
,# 15. enqueue and run in order
,# teardown
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# setup
,# 16. enqueueAtTop and run backwards
,# teardown
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# setup
,# 17. mix enqueue and enqueueAtTop
,# teardown
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# setup
,# 18. queues handled independently
,# teardown
,ok 73 all short operations completed before the long resolves
,# setup
,# 19. basic
,# teardown
,ok 74 sane
,# setup
,# 20. another
,# teardown
,ok 75 sane
,# setup
,# 21. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 76 specific error should be returned
,# setup
,ok 77 error should be null
,ok 78 error should be null
,# 22. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 79 specific error should be returned
,# setup
,ok 80 error should be null
,ok 81 error should be null
,# 23. should be able to call #stopListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65355
,2016-03-19 12:55:14.735 ThaliTest[1791:2966305] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 12:55:14.739 ThaliTest[1791:2966305] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-19 12:55:14.746 ThaliTest[1791:2966305] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 12:55:14.748 ThaliTest[1791:2966305] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-19 12:55:15.186 ThaliTest[1791:2966305] jxcore: stopAdvertisingAndListening
2016-03-19 12:55:15.186 ThaliTest[1791:2966305] THEMultipeerManager stopping peer
2016-03-19 12:55:15.187 ThaliTest[1791:2966305] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-19 12:55:15.188 ThaliTest[1791:2966305] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 12:55:15.190 ThaliTest[1791:2966305] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65357
,2016-03-19 12:55:15.928 ThaliTest[1791:2966305] jxcore: startListeningForAdvertisements
,2016-03-19 12:55:15.932 ThaliTest[1791:2966305] multipeer manager: start client restart timer: 0x1667d000
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 12:55:15.935 ThaliTest[1791:2966305] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
ok 89 error should be null
,2016-03-19 12:55:15.965 ThaliTest[1791:2966305] jxcore: startListeningForAdvertisements
2016-03-19 12:55:15.966 ThaliTest[1791:2966105] client: found new peer: F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9

```
