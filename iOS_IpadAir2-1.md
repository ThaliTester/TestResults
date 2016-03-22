#### Test 63680118d4cb974_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2B460680-B334-49C5-BBD4-0EA58B2B94E9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2B460680-B334-49C5-BBD4-0EA58B2B94E9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63680118d4cb974/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54796"
,(lldb)     command script import "/tmp/2B460680-B334-49C5-BBD4-0EA58B2B94E9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 14:36:38.785 ThaliTest[2029:3417186] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A7C30567-D672-4F2F-A9E9-016F4BC7B8D3/Library/Cookies/Cookies.binarycookies
,2016-03-22 14:36:39.185 ThaliTest[2029:3417186] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 14:36:39.186 ThaliTest[2029:3417186] Multi-tasking -> Device: YES, App: YES
,2016-03-22 14:36:39.205 ThaliTest[2029:3417186] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 14:36:41.153 ThaliTest[2029:3417186] Using UIWebView
,2016-03-22 14:36:41.160 ThaliTest[2029:3417186] [CDVTimer][handleopenurl] 0.371993ms
,2016-03-22 14:36:41.167 ThaliTest[2029:3417186] [CDVTimer][intentandnavigationfilter] 6.832004ms
,2016-03-22 14:36:41.168 ThaliTest[2029:3417186] [CDVTimer][gesturehandler] 0.330031ms
,2016-03-22 14:36:41.168 ThaliTest[2029:3417186] [CDVTimer][TotalPluginStartup] 9.078026ms
,2016-03-22 14:36:48.152 ThaliTest[2029:3417186] Resetting plugins due to page load.
,2016-03-22 14:36:51.914 ThaliTest[2029:3417186] Finished load of: file:///var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/index.html
,2016-03-22 14:36:52.124 ThaliTest[2029:3417186] JXcore Cordova plugin initializing
,2016-03-22 14:36:52.125 ThaliTest[2029:3417424] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 14:36:58.583 ThaliTest[2029:3417424] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 14:36:58.583 ThaliTest[2029:3417424] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 14:36:58.583 ThaliTest[2029:3417424] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:36:58.585 ThaliTest[2029:3417424] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/E35BC305-3C89-4F17-86AA-8A44A38383AA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 14:37:03.786 ThaliTest[2029:3417186] THREAD WARNING: ['JXcore'] took '4926.629639' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51021
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51023
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
,DEBUG createNativeListener: listening 51026
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
,DEBUG createNativeListener: listening 51030
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
,DEBUG createNativeListener: listening 51035
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
,DEBUG createNativeListener: listening 51039
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
,DEBUG createNativeListener: listening 51043
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
,DEBUG createNativeListener: listening 51047
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
,DEBUG createNativeListener: listening 51051
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
,DEBUG createNativeListener: listening 51103
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
,DEBUG createNativeListener: listening 51107
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
,DEBUG createNativeListener: listening 51119
,2016-03-22 14:39:15.966 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.968 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-22 14:39:15.974 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:15.976 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-22 14:39:16.183 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:16.184 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:16.184 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,2016-03-22 14:39:16.186 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:16.188 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51121
,2016-03-22 14:39:16.562 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,2016-03-22 14:39:16.564 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:16.567 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-22 14:39:16.593 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:16.595 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-22 14:39:16.875 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:16.875 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:16.876 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:16.877 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,2016-03-22 14:39:16.878 ThaliTest[2029:3417424] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:16.881 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51123
,2016-03-22 14:39:17.475 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:39:17.476 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:1
,2016-03-22 14:39:17.478 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
,2016-03-22 14:39:17.478 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:1
,2016-03-22 14:39:17.479 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-22 14:39:17.512 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:39:17.512 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:17.513 ThaliTest[2029:3417424] multipeer manager: stop client timer
,2016-03-22 14:39:17.514 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:2
,2016-03-22 14:39:17.515 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:39:17.515 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:2
2016-03-22 14:39:17.515 ,ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-22 14:39:18.069 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:18.069 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:18.070 ThaliTest[2029:3417424] multipeer manager: stop client timer
,2016-03-22 14:39:18.072 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,2016-03-22 14:39:18.074 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 14:39:18.076 ThaliTest[2029:34174,24] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51128
,2016-03-22 14:39:19.617 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:19.618 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
2016-03-22 14:39:19.618 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,2016-03-22 14:39:19.624 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:19.625 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:19.625 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-22 14:39:19.933 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:19.933 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:19.934 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,2016-03-22 14:39:19.935 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:19.937 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 110 error should be null
,ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51130
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-22 14:39:20.537 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:20.537 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:20.538 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,2016-03-22 14:39:20.539 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:20.541 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51132
,2016-03-22 14:39:20.963 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,2016-03-22 14:39:20.964 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:20.971 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,2016-03-22 14:39:20.985 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:20.986 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:3
,2016-03-22 14:39:20.987 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:3
2016-03-22 14:39:20.987 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
,ok 118 discovery state matches
,ok 119 advertising state matches
,# teardown
,2016-03-22 14:39:21.189 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:21.189 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:21.190 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
2016-03-22 14:39:21.191 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,2016-03-22 14:39:21.193 ThaliTest[2029:3417424] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:21.197 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
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
,2016-03-22 14:39:26.569 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,2016-03-22 14:39:26.570 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:26.572 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 135 Can call startListeningForAdvertisements without error
,2016-03-22 14:39:26.579 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,2016-03-22 14:39:26.579 ThaliTest[2029:3417424] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:26.583 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-22 14:39:26.899 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:26.901 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:26.904 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:26.904 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:26.905 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-22 14:39:27.437 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,2016-03-22 14:39:27.438 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:27.440 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 139 Can call startListeningForAdvertisements without error
,2016-03-22 14:39:27.444 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:39:27.446 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 140 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-03-22 14:39:27.563 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,2016-03-22 14:39:27.563 ThaliTest[2029:3417424] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:27.567 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:27.569 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:27.570 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:27.571 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-22 14:39:31.172 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:31.173 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:4
,2016-03-22 14:39:31.175 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:39:31.175 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:4
,2016-03-22 14:39:31.176 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-22 14:39:31.182 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:31.183 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
2016-03-22 14:39:31.18,3 ThaliTest[2029:3417424] multipeer manager: stop client timer
2016-03-22 14:39:31.183 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-22 14:39:32.000 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:39:32.003 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:32.005 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:32.006 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:32.006 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 146 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-22 14:39:33.779 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:39:33.780 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:5
,2016-03-22 14:39:33.781 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:39:33.781 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:5
2016-03-22 14:39:33.782 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 147 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 14:39:33.785 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
2016-03-22 14:39:33.785 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
2016-03-22 14:39:33.786 ThaliTest[2029:3417424] multipeer manager: stop client timer
2016-03-22 14:39:33.786 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:6
2016-03-22 14:39:33.787 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:39:33.787 ThaliTest[2029:,3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:6
2016-03-22 14:39:33.788 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without erro,r
,# teardown
,2016-03-22 14:39:34.357 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:39:34.359 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:34.362 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
2016-03-22 14:39:34.362 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:34.363 ThaliTest[2029:3417424] multipeer manager: stop client timer
2016-03-22 14:39:34.364 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 150 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. peerAvailabilityChange is called
,2016-03-22 14:39:34.952 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:39:34.953 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:7
,2016-03-22 14:39:34.954 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:39:34.955 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:7
2016-03-22 14:39:34.955 ,ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 151 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-22 14:39:34.962 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-22 14:39:34.965 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 152 Can call startListeningForAdvertisements without error
,2016-03-22 14:39:36.322 ThaliTest[2029:3417186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,ok 153 peers must be an array
,ok 154 peers must not be zero-length
,ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-22 14:39:36.689 ThaliTest[2029:3417186] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
,2016-03-22 14:39:40.149 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:39:40.152 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 159 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:39:40.154 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:39:40.154 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:39:40.155 ThaliTest[2029:3417424] multipeer manager: stop client timer
2016-03-22 14:39:40.156 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Can connect to a remote peer
,2016-03-22 14:40:03.203 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:40:03.204 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
,2016-03-22 14:40:03.205 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:40:03.205 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:8
2016-03-22 14:40:03.205 ,ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
,ok 161 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 14:40:03.209 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 14:40:03.213 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-22 14:40:03.635 ThaliTest[2029:3417186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7","pleaseConnect":0}]
,2016-03-22 14:40:03.639 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:03.640 ThaliTest[2029:3417424] client session: connect
2016-03-22 14:40:03.641 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:04.040 ThaliTest[2029:3417186] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"46287C39-66D9-4C88-AB7B-A74C4F9B045C:7","pleaseConnect":0}]
,2016-03-22 14:40:04.877 ThaliTest[2029:3417879] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:04.878 ThaliTest[2029:3417879] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:04.878 ThaliTest[2029:3417879] client session: disconnect
2016-03-22 14:40:04.878 ThaliTest[2029:3417879] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:04.879 ThaliTest[2029:3417879] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:04.880 ThaliTest[2029:3417879] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 14:40:07.887 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:07.887 ThaliTest[2029:3417424] client session: connect
2016-03-22 14:40:07.888 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:08.808 ThaliTest[2029:3417854] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:08.809 ThaliTest[2029:3417854] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:08.809 ThaliTest[2029:3417854] client session: disconnect
,2016-03-22 14:40:08.810 ThaliTest[2029:3417854] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:08.811 ThaliTest[2029:3417854] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:08.811 ThaliTest[2029:3417854] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-22 14:40:11.819 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:11.820 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:40:11.820 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:12.617 ThaliTest[2029:3417879] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:12.617 ThaliTest[2029:3417879] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:12.6,18 ThaliTest[2029:3417879] client session: disconnect
2016-03-22 14:40:12.618 ThaliTest[2029:3417879] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:12.620 ThaliTest[2029:3417879] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:12.620 ThaliTest[2029:3417879] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 14:40:15.627 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:15.628 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:40:15.628 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:16.616 ThaliTest[2029:3417854] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:16.616 ThaliTest[2029:3417854] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:16.617 ThaliTest[2029:3417854] client session: disconnect
,2016-03-22 14:40:16.617 ThaliTest[2029:3417854] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:16.619 ThaliTest[2029:3417854] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:16.619 ThaliTest[2029:3417854] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 14:40:19.627 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:19.628 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:40:19.629 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:20.109 ThaliTest[2029:3417853] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:20.109 ThaliTest[2029:3417853] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:20.1,09 ThaliTest[2029:3417853] client session: disconnect
2016-03-22 14:40:20.110 ThaliTest[2029:3417853] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:20.113 ThaliTest[2029:3417853] client session: fireConnectCallb,ack: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:20.114 ThaliTest[2029:3417853] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 5
,2016-03-22 14:40:23.129 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
2016-03-22 14:40:23.130 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:40:23.130 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:23.207 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:40:23.237 ThaliTest[2029:3417186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:23.237 ThaliTest[2029:3417186] client: found updated peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"46287C39-66D9-4C88-AB7B-A74C4F9B045C:8","pleaseConnect":0}]
,2016-03-22 14:40:43.207 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:40:43.229 ThaliTest[2029:3417186] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:40:43.230 ThaliTest[2029:3417186] client: found updated peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8","pleaseConnect":0}]
,2016-03-22 14:40:56.095 ThaliTest[2029:3418052] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:40:56.096 ThaliTest[2029:3418052] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:56.097 ThaliTest[2029:3418052] client session: disconnect
,2016-03-22 14:40:56.097 ThaliTest[2029:3418052] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:40:56.098 ThaliTest[2029:3418052] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:40:56.099 ThaliTest[2029:3418052] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 14:40:59.115 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:40:59.116 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:40:59.117 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:40:59.260 ThaliTest[2029:3418053] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:59.262 ThaliTest[2029:3418053] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:59.2,62 ThaliTest[2029:3418053] client session: disconnect
2016-03-22 14:40:59.262 ThaliTest[2029:3418053] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:40:59.263 ThaliTest[2029:3418053] client session: fireConnectCallb,ack: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:40:59.263 ThaliTest[2029:3418053] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-22 14:41:02.278 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:41:02.279 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:02.280 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:02.728 ThaliTest[2029:3418053] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:02.728 ThaliTest[2029:3418053] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:02.729 ThaliTest[2029:3418053] client session: disconnect
2016-03-22 14:41:02.729 ThaliTest[2029:3418053] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:02.729 ThaliTest[2029:3418053] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:02.730 ThaliTest[2029:3418053] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 14:41:03.207 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:41:03.228 ThaliTest[2029:3417186] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
2016-03-22 14:41:03.228 ThaliTest[2029:3417186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:05.741 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:41:05.742 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:05.742 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:05.942 ThaliTest[2029:3418067] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:05.943 ThaliTest[2029:3418067] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:05.943 ThaliTest[2029:3418067] client session: disconnect
2016-03-22 14:41:05.943 ThaliTest[2029:3418067] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:05.944 ThaliTest[2029:3418067] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:05.945 ThaliTest[2029:3418067] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 14:41:08.955 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:7
,2016-03-22 14:41:08.956 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:08.956 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:09.160 ThaliTest[2029:3417996] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:09.160 ThaliTest[2029:3417996] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:09.1,61 ThaliTest[2029:3417996] client session: disconnect
2016-03-22 14:41:09.161 ThaliTest[2029:3417996] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:09.162 ThaliTest[2029:3417996] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:09.162 ThaliTest[2029:3417996] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 163 Connect failed!
,  ---
,    operator: fail
,  ...
,# teardown
,2016-03-22 14:41:09.947 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:41:09.949 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 164 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:41:09.952 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
2016-03-22 14:41:09.952 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:41:09.954 ThaliTest[2029:3417424] multipeer manager: stop client timer
2016-03-22 14:41:09.954 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 165 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can shift large amounts of data
,2016-03-22 14:41:12.177 ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 14:41:12.178 ThaliTest[2029:3417424] server: starting E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
,2016-03-22 14:41:12.179 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
2016-03-22 14:41:12.180 ThaliTest[2029:3417424] THEMultipeerManager initialized peer E37C719D-F7A3-448B-B4C9-69FDBA30F0B4:9
2016-03-22 14:41:12.180 ,ThaliTest[2029:3417424] jxcore: startUpdateAdvertisingAndListening: success
ok 166 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 14:41:12.184 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 14:41:12.186 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
ok 167 Can call startListeningForAdvertisements without error
,2016-03-22 14:41:12.197 ThaliTest[2029:3417186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:12.198 ThaliTest[2029:3417186] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:8
,2016-03-22 14:41:12.200 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:12.200 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:12.201 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:13.348 ThaliTest[2029:3418067] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:13.349 ThaliTest[2029:3418067] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:13.349 ThaliTest[2029:3418067] client session: disconnect
2016-03-22 14:41:13.349 ThaliTest[2029:3418067] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:13.350 ThaliTest[2029:3418067] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:13.350 ThaliTest[2029:3418067] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 14:41:16.364 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:16.365 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:16.366 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:16.518 ThaliTest[2029:3418067] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:16.518 ThaliTest[2029:3418067] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:16.519 ThaliTest[2029:3418067] client session: disconnect
2016-03-22 14:41:16.520 ThaliTest[2029:3418067] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:16.521 ThaliTest[2029:3418067] client sess,ion: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:16.521 ThaliTest[2029:3418067] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-22 14:41:19.530 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:19.531 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:19.531 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:19.639 ThaliTest[2029:3418053] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:19.639 ThaliTest[2029:3418053] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:19.639 ThaliTest[2029:3418053] client session: disconnect
,2016-03-22 14:41:19.640 ThaliTest[2029:3418053] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:19.641 ThaliTest[2029:3418053] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:19.642 ThaliTest[2029:3418053] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 14:41:22.656 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:22.656 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:22.657 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:22.787 ThaliTest[2029:3418127] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:22.787 ThaliTest[2029:3418127] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:22.787 ThaliTest[2029:3418127] client session: disconnect
,2016-03-22 14:41:22.788 ThaliTest[2029:3418127] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:22.790 ThaliTest[2029:3418127] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:22.790 ThaliTest[2029:3418127] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 14:41:25.796 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:25.797 ThaliTest[2029:3417424] client session: connect
2016-03-22 14:41:25.797 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:25.928 ThaliTest[2029:3418067] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:25.928 ThaliTest[2029:3418067] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:25.928 ThaliTest[2029:3418067] client session: disconnect
2016-03-22 14:41:25.929 ThaliTest[2029:3418067] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:25.931 ThaliTest[2029:3418067] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:25.931 ThaliTest[2029:3418067] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 14:41:28.943 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:28.944 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:28.944 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:29.025 ThaliTest[2029:3418127] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:41:29.026 ThaliTest[2029:3418127] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:41:29.026 ThaliTest[2029:3418127] client session: disconnect
2016-03-22 14:41:29.026 ThaliTest[2029:3418127] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:29.028 ThaliTest[2029:3418127] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:41:29.029 ThaliTest[2029:3418127] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 14:41:32.037 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:32.038 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:41:32.038 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:41:32.181 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:41:32.205 ThaliTest[2029:3417186] client: found updated peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:9
2016-03-22 14:41:32.206 ThaliTest[2029:3417186] client: found updated peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:41:52.181 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:41:52.205 ThaliTest[2029:3417186] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:9
2016-03-22 14:41:52.205 ThaliTest[2029:3417186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:05.018 ThaliTest[2029:3418214] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:42:05.019 ThaliTest[2029:3418214] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:42:05.019 ThaliTest[2029:3418214] client session: disconnect
,2016-03-22 14:42:05.020 ThaliTest[2029:3418214] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:05.022 ThaliTest[2029:3418214] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:42:05.022 ThaliTest[2029:3418214] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-22 14:42:08.031 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:42:08.032 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:42:08.032 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:08.433 ThaliTest[2029:3418127] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:08.435 ThaliTest[2029:3418127] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:42:08.435 ThaliTest[2029:3418127] client session: disconnect
2016-03-22 14:42:08.436 ThaliTest[2029:3418127] client session:, stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:08.436 ThaliTest[2029:3418127] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:42:08.437 ThaliTest[2029:3418127] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 14:42:11.445 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
,2016-03-22 14:42:11.446 ThaliTest[2029:3417424] client session: connect
,2016-03-22 14:42:11.446 ThaliTest[2029:3417424] client session: stateChange:0->1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:11.543 ThaliTest[2029:3418241] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:42:11.543 ThaliTest[2029:3418241] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:42:11.545 ThaliTest[2029:3418241] client session: disconnect
2016-03-22 14:42:11.545 ThaliTest[2029:3418241] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
2016-03-22 14:42:11.546 ThaliTest[2029:3418241] client sess,ion: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
2016-03-22 14:42:11.546 ThaliTest[2029:3418241] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 14:42:12.181 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:42:12.201 ThaliTest[2029:3417186] client: found existing peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:9
2016-03-22 14:42:12.201 ThaliTest[2029:3417186] client: found existing peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:14.563 ThaliTest[2029:3417424] jxcore: connect 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:8
2016-03-22 14:42:14.564 ThaliTest[2029:3417424] client session: connect
2016-03-22 14:42:14.564 ThaliTest[2029:3417424] client session: stateChange:0->,1 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:14.665 ThaliTest[2029:3418215] client session: not connected 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:14.666 ThaliTest[2029:3418215] client session: onLinkFailure: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:42:14.667 ThaliTest[2029:3418215] client session: disconnect
,2016-03-22 14:42:14.667 ThaliTest[2029:3418215] client session: stateChange:1->0 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:14.668 ThaliTest[2029:3418215] client session: fireConnectCallback: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:42:14.668 ThaliTest[2029:3418215] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 168 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-03-22 14:42:20.515 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 14:42:20.517 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 169 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 14:42:20.520 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:42:20.520 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
,2016-03-22 14:42:20.521 ThaliTest[2029:3417424] multipeer manager: stop client timer
2016-03-22 14:42:20.522 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2016-03-22 14:42:21.336 ThaliTest[2029:3417424] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 14:42:21.337 ThaliTest[2029:3417424] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 14:42:21.339 ThaliTest[2029:3417424] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:21.342 ThaliTest[2029:3417424] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 40. #startListeningForAdvertisements should fail if start not called
,ok 171 specific error should be returned
,# teardown
,# setup
,2016-03-22 14:42:23.188 ThaliTest[2029:3417424] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 14:42:23.190 ThaliTest[2029:3417424] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 14:42:23.191 ThaliTest[2029:3417424] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:23.193 ThaliTest[2029:3417424] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,ok 172 specific error should be returned
,# teardown
,# setup
,2016-03-22 14:42:23.835 ThaliTest[2029:3417424] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 14:42:23.836 ThaliTest[2029:3417424] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 14:42:23.837 ThaliTest[2029:3417424] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:23.840 ThaliTest[2029:3417424] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 42. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51181
,2016-03-22 14:42:24.232 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:42:24.235 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 173 no errors
,2016-03-22 14:42:24.238 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:42:24.240 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,ok 174 still no errors
,# teardown
,2016-03-22 14:42:24.376 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening
,2016-03-22 14:42:24.376 ThaliTest[2029:3417424] THEMultipeerManager stopping peer
2016-03-22 14:42:24.377 ThaliTest[2029:3417424] jxcore: stopAdvertisingAndListening: success
,2016-03-22 14:42:24.378 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 14:42:24.380 ThaliTest[2029:3417424] jxcore: stopListeningForAdvertisements: success
,# setup
,2016-03-22 14:42:24.738 ThaliTest[2029:3417424] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 14:42:24.739 ThaliTest[2029:3417424] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 14:42:24.740 ThaliTest[2029:3417424] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 14:42:24.742 ThaliTest[2029:3417424] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# 43. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51183
,2016-03-22 14:42:24.907 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
,2016-03-22 14:42:24.908 ThaliTest[2029:3417424] multipeer manager: start client restart timer: 0x17650280
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:42:24.911 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 175 no errors
,2016-03-22 14:42:24.914 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 14:42:24.917 ThaliTest[2029:3417424] jxcore: startListeningForAdvertisements: success
,ok 176 still no errors
,# teardown
,2016-03-22 14:42:24.927 ThaliTest[2029:3417186] client: found new peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA:9
,2016-03-22 14:42:24.931 ThaliTest[2029:3417186] client: found new peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-22 14:42:38.692 ThaliTest[2029:3417186] client: lost peer: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:42:38.692 ThaliTest[2029:3417186] client session: onPeerLost: 46287C39-66D9-4C88-AB7B-A74C4F9B045C
,2016-03-22 14:42:38.693 ThaliTest[2029:3417186] client: lost peer: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:42:38.693 ThaliTest[2029:3417186] client session: onPeerLost: 4C3ACECD-4F82-43E7-BE78-A6DF083690BA
,2016-03-22 14:42:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:43:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:43:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:43:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:44:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:44:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:44:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:45:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:45:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:45:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:46:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:46:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:46:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:47:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:47:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:47:44.909 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:48:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:48:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:48:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:49:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:49:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:49:44.909 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:50:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:50:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:50:44.909 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:51:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:51:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:51:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:52:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:52:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:52:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:53:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:53:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:53:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:54:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:54:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:54:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:55:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:55:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:55:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:56:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:56:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:56:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:57:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:57:24.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:57:44.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:58:04.910 ThaliTest[2029:3417186] multipeer manager: restart client
,2016-03-22 14:58:24.910 ThaliTest[2029:3417186] multipeer manager: restart client

```
