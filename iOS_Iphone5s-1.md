#### Test 63998117be38304_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63998117be38304/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/48733A4C-9154-4ACC-9C62-66D5980D4C4B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/48733A4C-9154-4ACC-9C62-66D5980D4C4B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63998117be38304/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63998117be38304/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55468"
,(lldb)     command script import "/tmp/48733A4C-9154-4ACC-9C62-66D5980D4C4B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 08:45:40.673 ThaliTest[2104:3700664] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A8193D4D-DA2D-443F-8757-7DFFFF55E7F4/Library/Cookies/Cookies.binarycookies
,2016-03-24 08:45:41.071 ThaliTest[2104:3700664] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 08:45:41.073 ThaliTest[2104:3700664] Multi-tasking -> Device: YES, App: YES
,2016-03-24 08:45:41.097 ThaliTest[2104:3700664] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 08:45:42.946 ThaliTest[2104:3700664] Using UIWebView
,2016-03-24 08:45:42.956 ThaliTest[2104:3700664] [CDVTimer][handleopenurl] 0.452042ms
,2016-03-24 08:45:42.965 ThaliTest[2104:3700664] [CDVTimer][intentandnavigationfilter] 7.910967ms
2016-03-24 08:45:42.966 ThaliTest[2104:3700664] [CDVTimer][gesturehandler] 0.380039ms
2016-03-24 08:45:42.966 ThaliTest[2104:3700664] [CDVTimer][TotalPluginS,tartup] 10.582983ms
,2016-03-24 08:45:50.229 ThaliTest[2104:3700664] Resetting plugins due to page load.
,2016-03-24 08:45:54.074 ThaliTest[2104:3700664] Finished load of: file:///var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/index.html
,2016-03-24 08:45:54.326 ThaliTest[2104:3700664] JXcore Cordova plugin initializing
,2016-03-24 08:45:54.328 ThaliTest[2104:3700876] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 08:46:02.934 ThaliTest[2104:3700876] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 08:46:02.935 ThaliTest[2104:3700876] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 08:46:02.935 ThaliTest[2104:3700876] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 08:46:02.937 ThaliTest[2104:3700876] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E8CD1CFE-E923-428E-B270-F6EBD6142EBB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 08:46:09.911 ThaliTest[2104:3700664] THREAD WARNING: ['JXcore'] took '6598.816162' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51808
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51810
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
,DEBUG createNativeListener: listening 51813
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
,DEBUG createNativeListener: listening 51817
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
,DEBUG createNativeListener: listening 51822
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
,DEBUG createNativeListener: listening 51826
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
,DEBUG createNativeListener: listening 51830
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
,DEBUG createNativeListener: listening 51834
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
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51838
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
,DEBUG createNativeListener: listening 51890
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
,DEBUG createNativeListener: listening 51894
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
,DEBUG createNativeListener: listening 51906
,2016-03-24 08:47:56.577 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 08:47:56.581 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-24 08:47:56.588 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 08:47:56.591 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-24 08:47:56.738 ThaliTest[2104:3700876] jxcore: stopAdvertisingAndListening
2016-03-24 08:47:56.739 ThaliTest[2104:3700876] THEMultipeerManager stopping peer
2016-03-24 08:47:56.739 ThaliTest[2104:3700876] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 08:47:56.740 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 08:47:56.742 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51908
,2016-03-24 08:47:57.021 ThaliTest[2104:3700876] jxcore: startListeningForAdvertisements
,2016-03-24 08:47:57.025 ThaliTest[2104:3700876] multipeer manager: start client restart timer: 0x165acb30
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 08:47:57.029 ThaliTest[2104:3700876] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-24 08:47:57.182 ThaliTest[2104:3700876] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 08:47:57.185 ThaliTest[2104:3700876] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-24 08:47:57.417 ThaliTest[2104:3700876] jxcore: stopAdvertisingAndListening
2016-03-24 08:47:57.417 ThaliTest[2104:3700876] THEMultipeerManager stopping peer
2016-03-24 08:47:57.418 ThaliTest[2104:3700876] jxcore: stopAdvertisingAndListening: suc,cess
,2016-03-24 08:47:57.420 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements
2016-03-24 08:47:57.421 ThaliTest[2104:3700876] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 08:47:57.423 ThaliTest[2104:3700876] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51910
,2016-03-24 08:47:59.143 ThaliTest[2104:3700876] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 08:47:59.145 ThaliTest[2104:3700876] server: starting EBA29E46-2D28-43EB-B896-31A127721C1F:1
,2016-03-24 08:47:59.146 ThaliTest[2104:3700876] multipeer manager: start client restart timer: 0x165acb30
2016-03-24 08:47:59.147 ThaliTest[2104:3700876] THEMultipeerManager initialized peer EBA29E46-2D28-43EB-B896-31A127721C1F:1
2016-03-24 08:47:59.148 ,ThaliTest[2104:3700876] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-24 08:47:59.181 ThaliTest[2104:3700876] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 08:47:59.182 ThaliTest[2104:3700876] THEMultipeerManager stopping peer
,2016-03-24 08:47:59.184 ThaliTest[2104:3700876] multipeer manager: stop client timer
2016-03-24 08:47:59.185 ThaliTest[2104:3700876] server: starting EBA29E46-2D28-43EB-B896-31A127721C1F:2
2016-03-24 08:47:59.186 ThaliTest[2104:3700876] multipeer manager,: start client restart timer: 0x165acb30
2016-03-24 08:47:59.187 ThaliTest[2104:3700876] THEMultipeerManager initialized peer EBA29E46-2D28-43EB-B896-31A127721C1F:2
2016-03-24 08:47:59.188 ThaliTest[2104:3700876] jxcore: startUpdateAdvertisingAndListenin,g: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-24 08:48:00.734 ThaliTest[2104:3700664] client: found new peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:48:03.364 ThaliTest[2104:3700664] client: found new peer: 00085AB7-1FE7-49C7-9134-44FA4AE132E8:2
,2016-03-24 08:48:05.450 ThaliTest[2104:3700664] client: lost peer: 00085AB7-1FE7-49C7-9134-44FA4AE132E8
2016-03-24 08:48:05.450 ThaliTest[2104:3700664] client session: onPeerLost: 00085AB7-1FE7-49C7-9134-44FA4AE132E8
,2016-03-24 08:48:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:48:19.202 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:48:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:48:39.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:48:43.608 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:48:43.609 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:48:44.181 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:48:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:49:00.018 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:49:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:49:19.197 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:49:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:49:39.215 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:49:39.654 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:49:39.656 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:49:42.350 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:49:51.332 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:49:51.332 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:49:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:49:59.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:50:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:50:19.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:50:35.670 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:50:35.671 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:50:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:50:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:50:59.539 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:51:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:51:19.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:51:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:51:39.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:51:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:51:59.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:52:09.644 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:52:09.645 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:52:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:52:19.206 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:52:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:52:39.209 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:52:59.187 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:52:59.198 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:53:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:53:19.200 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:53:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:53:39.201 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:53:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:53:59.215 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:54:05.657 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:54:05.657 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:54:05.900 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:54:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:54:19.202 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:54:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:54:39.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:54:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:54:59.213 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:55:00.480 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:55:00.480 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:55:18.844 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:55:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:55:19.213 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:55:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:55:39.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:55:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:55:59.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:56:10.591 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:56:10.591 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:56:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:56:19.208 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:56:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:56:39.208 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,appEnteredForeground wasn't registered
,2016-03-24 08:56:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:56:59.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:57:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:57:19.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:57:25.670 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:57:25.670 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:57:25.961 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:57:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:57:39.216 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,Disconnected from the test server
,2016-03-24 08:57:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:57:59.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:58:00.736 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:58:00.736 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:58:01.833 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:58:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:58:19.217 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:58:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:58:39.217 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:58:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:58:59.218 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:59:11.792 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 08:59:11.793 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 08:59:12.283 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:59:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:59:19.201 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:59:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:59:39.201 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 08:59:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 08:59:59.212 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:00:09.451 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 09:00:09.452 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 09:00:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:00:19.209 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:00:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:00:39.208 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:00:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:00:59.207 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:01:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:01:19.206 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:01:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:01:39.202 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:01:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:01:59.223 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:02:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:02:19.213 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:02:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:02:39.213 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:02:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:02:59.213 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:03:15.663 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 09:03:15.663 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 09:03:17.411 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:03:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:03:19.200 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:03:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:03:39.201 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:03:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:03:59.201 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:04:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:04:19.214 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:04:33.438 ThaliTest[2104:3700664] client: lost peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
2016-03-24 09:04:33.439 ThaliTest[2104:3700664] client session: onPeerLost: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB
,2016-03-24 09:04:33.801 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:04:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:04:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:04:59.202 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:05:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:05:19.203 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:05:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:05:39.205 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:05:59.187 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:05:59.202 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:06:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:06:19.201 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:06:39.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:06:39.204 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:06:59.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:06:59.197 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
,2016-03-24 09:07:19.188 ThaliTest[2104:3700664] multipeer manager: restart client
,2016-03-24 09:07:19.204 ThaliTest[2104:3700664] client: found existing peer: BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2

```
