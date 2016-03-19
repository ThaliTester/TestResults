#### Test 62548124ca582f4_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124ca582f4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2EA3AB4F-23F7-40A3-827A-5AEBABECA722/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2EA3AB4F-23F7-40A3-827A-5AEBABECA722/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124ca582f4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124ca582f4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52986"
,(lldb)     command script import "/tmp/2EA3AB4F-23F7-40A3-827A-5AEBABECA722/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-19 11:44:20.216 ThaliTest[1799:2944220] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/35C1234E-182D-4471-9451-CDF5B07EE986/Library/Cookies/Cookies.binarycookies
,2016-03-19 11:44:20.596 ThaliTest[1799:2944220] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-19 11:44:20.597 ThaliTest[1799:2944220] Multi-tasking -> Device: YES, App: YES
,2016-03-19 11:44:20.617 ThaliTest[1799:2944220] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-19 11:44:22.622 ThaliTest[1799:2944220] Using UIWebView
,2016-03-19 11:44:22.631 ThaliTest[1799:2944220] [CDVTimer][handleopenurl] 0.392020ms
,2016-03-19 11:44:22.638 ThaliTest[1799:2944220] [CDVTimer][intentandnavigationfilter] 7.090032ms
,2016-03-19 11:44:22.639 ThaliTest[1799:2944220] [CDVTimer][gesturehandler] 0.369012ms
,2016-03-19 11:44:22.640 ThaliTest[1799:2944220] [CDVTimer][TotalPluginStartup] 9.486020ms
,2016-03-19 11:44:29.996 ThaliTest[1799:2944220] Resetting plugins due to page load.
,2016-03-19 11:44:33.473 ThaliTest[1799:2944220] Finished load of: file:///var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/index.html
,2016-03-19 11:44:33.676 ThaliTest[1799:2944220] JXcore Cordova plugin initializing
,2016-03-19 11:44:33.677 ThaliTest[1799:2944455] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-19 11:44:40.108 ThaliTest[1799:2944455] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 11:44:40.108 ThaliTest[1799:2944455] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-19 11:44:40.109 ThaliTest[1799:2944455] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:44:40.110 ThaliTest[1799:2944455] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FE90B26-4321-4DC9-8944-2CA829DF3DEF/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-19 11:44:45.327 ThaliTest[1799:2944220] THREAD WARNING: ['JXcore'] took '4940.451904' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65185
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65187
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
,DEBUG createNativeListener: listening 65190
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
,DEBUG createNativeListener: listening 65194
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
,DEBUG createNativeListener: listening 65199
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
,DEBUG createNativeListener: listening 65203
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
,DEBUG createNativeListener: listening 65207
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
,DEBUG createNativeListener: listening 65211
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
,DEBUG createNativeListener: listening 65216
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
,DEBUG createNativeListener: listening 65268
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
,DEBUG createNativeListener: listening 65272
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
,DEBUG createNativeListener: listening 65284
,2016-03-19 11:48:01.374 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:01.377 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-19 11:48:01.382 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:01.385 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-19 11:48:01.620 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:01.620 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:01.621 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:48:01.623 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:01.625 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65286
,2016-03-19 11:48:02.024 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,2016-03-19 11:48:02.026 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:02.029 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-19 11:48:02.055 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:02.058 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-19 11:48:02.460 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:02.460 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:02.461 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:48:02.462 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,2016-03-19 11:48:02.463 ThaliTest[1799:2944455] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:02.466 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65288
,2016-03-19 11:48:02.970 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:48:02.971 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:1
,2016-03-19 11:48:02.972 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:02.973 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:1
2016-03-19 11:48:02.973 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-19 11:48:02.999 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:03.000 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:03.001 ThaliTest[1799:2944455] multipeer manager: stop client timer
2016-03-19 11:48:03.001 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:2
,2016-03-19 11:48:03.004 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:03.005 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:2
2016-03-19 11:48:03.005 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-19 11:48:03.847 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:03.847 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:03.848 ThaliTest[1799:2944455] multipeer manager: stop client timer
2016-03-19 11:48:03.848 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:48:03.852 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:03.858 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65293
,2016-03-19 11:48:04.483 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:04.483 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:04.484 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-19 11:48:04.491 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:04.491 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:04.492 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-19 11:48:04.903 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:04.903 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:04.904 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:48:04.905 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:04.907 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65295
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-19 11:48:05.593 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:05.593 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:05.594 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:48:05.595 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:05.597 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65297
,2016-03-19 11:48:06.071 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,2016-03-19 11:48:06.072 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:06.077 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
,2016-03-19 11:48:06.095 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:48:06.095 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:3
,2016-03-19 11:48:06.097 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:3
2016-03-19 11:48:06.097 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-19 11:48:06.403 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:06.403 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:06.404 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:48:06.405 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
2016-03-19 11:48:06.406 ThaliTest[1799:2944455] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:06.407 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 114 error should be null
,ok 115 error should be null
,# 29. does not send duplicate availability changes
,# teardown
,ok 116 should be called once
,ok 117 should not have been called more than once
,# setup
,ok 118 error should be null
,ok 119 error should be null
,# 30. can get the network status
,# teardown
,ok 120 network status should have certain non-empty properties
,# setup
,ok 121 error should be null
,ok 122 error should be null
,# 31. wifi peer is marked unavailable if announcements stop
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 123 host address should match
,ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-19 11:48:11.642 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,2016-03-19 11:48:11.643 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:11.646 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:11.649 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
2016-03-19 11:48:11.650 ThaliTest[1799:2944455] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:11.652 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-19 11:48:11.782 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:11.785 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:11.787 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:11.788 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:11.788 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-19 11:48:11.980 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,2016-03-19 11:48:11.981 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:11.983 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:11.987 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:48:11.989 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-19 11:48:12.376 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,2016-03-19 11:48:12.377 ThaliTest[1799:2944455] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:48:12.380 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:12.382 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:12.383 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
2016-03-19 11:48:12.383 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-19 11:48:12.806 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:48:12.807 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:4
,2016-03-19 11:48:12.808 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:12.809 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:4
2016-03-19 11:48:12.809 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-19 11:48:12.811 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:12.812 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
2016-03-19 11:48:12.812 ThaliTest[1799:2944455] multipeer manager: stop client timer
20,16-03-19 11:48:12.813 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-19 11:48:13.434 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:48:13.436 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:13.439 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:13.439 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:13.440 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-19 11:48:13.730 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:48:13.731 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:5
,2016-03-19 11:48:13.732 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:13.732 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:5
2016-03-19 11:48:13.732 T,haliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-19 11:48:13.735 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
2016-03-19 11:48:13.736 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:13.736 ThaliTest[1799:2944455] multipeer manager: stop client timer
,2016-03-19 11:48:13.737 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:6
2016-03-19 11:48:13.738 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:13.738 ThaliTest[1799:294445,5] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:6
2016-03-19 11:48:13.738 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-19 11:48:13.856 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:48:13.858 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:13.861 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:48:13.861 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:13.862 ThaliTest[1799:2944455] multipeer manager: stop client timer
,2016-03-19 11:48:13.862 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-19 11:48:14.271 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:48:14.272 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
,2016-03-19 11:48:14.273 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:14.274 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7
2016-03-19 11:48:14.274 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-19 11:48:14.278 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"disc,overyActive":true}
2016-03-19 11:48:14.280 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:15.320 ThaliTest[1799:2944220] client: found new peer: BFF196CF-9326-4437-A343-829BABDB6CBC:7
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-19 11:48:15.918 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:48:15.920 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:48:15.922 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
2016-03-19 11:48:15.923 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:48:15.924 ThaliTest[1799:2944455] multipeer manager: stop client timer
2016-03-19 11:48:15.925 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-19 11:48:16.366 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:48:16.366 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
,2016-03-19 11:48:16.368 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:48:16.368 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8
2016-03-19 11:48:16.368 T,haliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-19 11:48:16.372 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-19 11:48:16.374 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-19 11:48:18.392 ThaliTest[1799:2944220] client: found new peer: BFF196CF-9326-4437-A343-829BABDB6CBC:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BFF196CF-9326-4437-A343-829BABDB6CBC:7","pleaseConnect":0}]
,2016-03-19 11:48:18.397 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:18.398 ThaliTest[1799:2944455] client session: connect
2016-03-19 11:48:18.399 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:18.912 ThaliTest[1799:2944873] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:18.913 ThaliTest[1799:2944873] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:18.913 ThaliTest[1799:2944873] client session: disconnect
2016-03-19 11:48:18.914 ThaliTest[1799:2944873] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:18.914 ThaliTest[1799:2944873] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:18.915 ThaliTest[1799:2944873] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-19 11:48:19.041 ThaliTest[1799:2944220] multipeer session: reset timer
,2016-03-19 11:48:19.042 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7)
,2016-03-19 11:48:21.927 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:21.928 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:21.929 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:22.116 ThaliTest[1799:2944873] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:22.116 ThaliTest[1799:2944873] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:22.1,16 ThaliTest[1799:2944873] client session: disconnect
,2016-03-19 11:48:22.117 ThaliTest[1799:2944873] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:22.118 ThaliTest[1799:2944873] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:48:22.118 ThaliTest[1799:2944873] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-19 11:48:25.125 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:25.126 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:25.126 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:25.263 ThaliTest[1799:2944873] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:25.264 ThaliTest[1799:2944873] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:48:25.264 ThaliTest[1799:2944873] client session: disconnect
,2016-03-19 11:48:25.265 ThaliTest[1799:2944873] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:25.267 ThaliTest[1799:2944873] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:25.267 ThaliTest[1799:2944873] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-19 11:48:28.271 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:28.272 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:28.273 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:28.358 ThaliTest[1799:2945971] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:28.359 ThaliTest[1799:2945971] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:28.359 ThaliTest[1799:2945971] client session: disconnect
2016-03-19 11:48:28.359 ThaliTest[1799:2945971] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:28.360 ThaliTest[1799:2945971] client session: fireConnectCallb,ack: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:28.360 ThaliTest[1799:2945971] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-19 11:48:31.368 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:31.369 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:31.369 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:31.463 ThaliTest[1799:2944873] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:31.463 ThaliTest[1799:2944873] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:31.465 ThaliTest[1799:2944873] client session: disconnect
2016-03-19 11:48:31.465 ThaliTest[1799:2944873] client session:, stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:31.466 ThaliTest[1799:2944873] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:31.466 ThaliTest[1799:2944873] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-19 11:48:31.950 ThaliTest[1799:2944220] multipeer session: reset timer
2016-03-19 11:48:31.951 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:48:31.951 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7)
,2016-03-19 11:48:34.479 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:34.480 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:34.480 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:34.631 ThaliTest[1799:2945980] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:34.631 ThaliTest[1799:2945980] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:34.631 ThaliTest[1799:2945980] client session: disconnect
2016-03-19 11:48:34.632 ThaliTest[1799:2945980] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:34.632 ThaliTest[1799:2945980] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:34.634 ThaliTest[1799:2945980] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-19 11:48:36.369 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:48:36.385 ThaliTest[1799:2944220] client: found updated peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BFF196CF-9326-4437-A343-829BABDB6CBC:8","pleaseConnect":0}]
,2016-03-19 11:48:37.651 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
2016-03-19 11:48:37.651 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:37.652 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:37.974 ThaliTest[1799:2944873] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:48:37.975 ThaliTest[1799:2944873] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:37.9,75 ThaliTest[1799:2944873] client session: disconnect
2016-03-19 11:48:37.975 ThaliTest[1799:2944873] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:37.977 ThaliTest[1799:2944873] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:37.977 ThaliTest[1799:2944873] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-19 11:48:40.988 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:40.989 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:40.989 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:41.397 ThaliTest[1799:2945980] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:48:41.397 ThaliTest[1799:2945980] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:41.3,98 ThaliTest[1799:2945980] client session: disconnect
,2016-03-19 11:48:41.398 ThaliTest[1799:2945980] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:41.399 ThaliTest[1799:2945980] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:41.399 ThaliTest[1799:2945980] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-19 11:48:44.412 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:44.413 ThaliTest[1799:2944455] client session: connect
2016-03-19 11:48:44.414 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:44.596 ThaliTest[1799:2945980] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:48:44.596 ThaliTest[1799:2945980] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:44.597 ThaliTest[1799:2945980] client session: disconnect
,2016-03-19 11:48:44.597 ThaliTest[1799:2945980] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:44.599 ThaliTest[1799:2945980] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:44.599 ThaliTest[1799:2945980] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-19 11:48:44.923 ThaliTest[1799:2944220] multipeer session: reset timer
2016-03-19 11:48:44.923 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:48:44.924 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7)
,2016-03-19 11:48:47.607 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:7
,2016-03-19 11:48:47.608 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:48:47.609 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:47.750 ThaliTest[1799:2945980] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:48:47.751 ThaliTest[1799:2945980] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:48:47.751 ThaliTest[1799:2945980] client session: disconnect
2016-03-19 11:48:47.753 ThaliTest[1799:2945980] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:48:47.753 ThaliTest[1799:2945980] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:48:47.754 ThaliTest[1799:2945980] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-19 11:48:56.369 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:48:56.382 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:49:16.369 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:49:16.384 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:49:17.355 ThaliTest[1799:2944220] multipeer session: reset timer
,2016-03-19 11:49:17.355 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:49:17.355 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7)
,2016-03-19 11:49:30.267 ThaliTest[1799:2944220] multipeer session: reset timer
2016-03-19 11:49:30.268 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:49:30.268 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7)
,2016-03-19 11:49:36.369 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:49:36.383 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:49:43.366 ThaliTest[1799:2944220] multipeer session: reset timer
,2016-03-19 11:49:43.366 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:49:43.366 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:7)
,2016-03-19 11:49:56.369 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:49:56.382 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:06.527 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:50:06.529 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:50:06.533 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:50:06.533 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:50:06.534 ThaliTest[1799:2944455] multipeer manager: stop client timer
2016-03-19 11:50:06.535 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 159 Should be able to call stopAdvertisingAndListening in teardown
# 38. Can shift large amounts of data
,# teardown
,2016-03-19 11:50:07.866 ThaliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening
,2016-03-19 11:50:07.866 ThaliTest[1799:2944455] server: starting F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
,2016-03-19 11:50:07.868 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
2016-03-19 11:50:07.868 ThaliTest[1799:2944455] THEMultipeerManager initialized peer F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9
2016-03-19 11:50:07.868 T,haliTest[1799:2944455] jxcore: startUpdateAdvertisingAndListening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-19 11:50:07.871 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-19 11:50:07.875 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
ok 161 Can call startListeningForAdvertisements without error
,2016-03-19 11:50:08.684 ThaliTest[1799:2944220] client: found new peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:08.686 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:08.687 ThaliTest[1799:2944455] client session: connect
2016-03-19 11:50:08.687 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:08.854 ThaliTest[1799:2944220] multipeer session: reset timer
,2016-03-19 11:50:08.854 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8)
,2016-03-19 11:50:09.257 ThaliTest[1799:2946278] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:09.258 ThaliTest[1799:2946278] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:09.258 ThaliTest[1799:2946278] client session: disconnect
,2016-03-19 11:50:09.259 ThaliTest[1799:2946278] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:09.260 ThaliTest[1799:2946278] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 1,1:50:09.260 ThaliTest[1799:2946278] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-19 11:50:12.273 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:12.274 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:50:12.274 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:12.630 ThaliTest[1799:2946279] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:12.631 ThaliTest[1799:2946279] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:50:12.632 ThaliTest[1799:2946279] client session: disconnect
2016-03-19 11:50:12.632 ThaliTest[1799:2946279] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:12.633 ThaliTest[1799:2946279] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:50:12.633 ThaliTest[1799:2946279] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-19 11:50:15.638 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:15.639 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:50:15.640 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:16.289 ThaliTest[1799:2946278] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:16.290 ThaliTest[1799:2946278] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:16.291 ThaliTest[1799:2946278] client session: disconnect
2016-03-19 11:50:16.291 ThaliTest[1799:2946278] client session:, stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:16.292 ThaliTest[1799:2946278] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:16.292 ThaliTest[1799:2946278] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-19 11:50:19.306 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:19.306 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:50:19.307 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:19.932 ThaliTest[1799:2946279] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:19.933 ThaliTest[1799:2946279] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:19.934 ThaliTest[1799:2946279] client session: disconnect
,2016-03-19 11:50:19.934 ThaliTest[1799:2946279] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:19.935 ThaliTest[1799:2946279] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:19.936 ThaliTest[1799:2946279] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-19 11:50:21.309 ThaliTest[1799:2944220] multipeer session: reset timer
,2016-03-19 11:50:21.310 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
2016-03-19 11:50:21.310 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8)
,2016-03-19 11:50:22.952 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:22.953 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:50:22.954 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:23.566 ThaliTest[1799:2946279] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:23.567 ThaliTest[1799:2946279] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:23.567 ThaliTest[1799:2946279] client session: disconnect
2016-03-19 11:50:23.567 ThaliTest[1799:2946279] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:23.569 ThaliTest[1799:2946279] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:23.569 ThaliTest[1799:2946279] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-19 11:50:26.584 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:26.585 ThaliTest[1799:2944455] client session: connect
2016-03-19 11:50:26.586 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:27.343 ThaliTest[1799:2946278] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:50:27.343 ThaliTest[1799:2946278] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:27.344 ThaliTest[1799:2946278] client session: disconnect
2016-03-19 11:50:27.344 ThaliTest[1799:2946278] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:27.346 ThaliTest[1799:2946278] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:50:27.346 ThaliTest[1799:2946278] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-19 11:50:27.869 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:50:27.883 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:30.353 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:30.354 ThaliTest[1799:2944455] client session: connect
2016-03-19 11:50:30.355 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:50:35.116 ThaliTest[1799:2944220] multipeer session: reset timer
2016-03-19 11:50:35.117 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:50:35.117 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8)
,2016-03-19 11:50:47.635 ThaliTest[1799:2944220] multipeer session: reset timer
,2016-03-19 11:50:47.636 ThaliTest[1799:2944220] server: disconnecting to refresh session (BFF196CF-9326-4437-A343-829BABDB6CBC)
,2016-03-19 11:50:47.636 ThaliTest[1799:2944220] server: rejecting invitation from BFF196CF-9326-4437-A343-829BABDB6CBC due to previous generation (F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:9 != F6111CA1-FBE0-4E62-AA40-FA3A5F5782C5:8)
,2016-03-19 11:50:47.869 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:50:47.885 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:03.339 ThaliTest[1799:2946427] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:51:03.340 ThaliTest[1799:2946427] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:51:03.340 ThaliTest[1799:2946427] client session: disconnect
2016-03-19 11:51:03.340 ThaliTest[1799:2946427] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:03.341 ThaliTest[1799:2946427] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:51:03.342 ThaliTest[1799:2946427] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-19 11:51:06.347 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:06.348 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:51:06.348 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:06.707 ThaliTest[1799:2946312] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:06.708 ThaliTest[1799:2946312] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:51:06.708 ThaliTest[1799:2946312] client session: disconnect
2016-03-19 11:51:06.708 ThaliTest[1799:2946312] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:06.710 ThaliTest[1799:2946312] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:51:06.710 ThaliTest[1799:2946312] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-19 11:51:07.869 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:51:07.884 ThaliTest[1799:2944220] client: found existing peer: BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:09.725 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:09.726 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:51:09.726 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:09.998 ThaliTest[1799:2946427] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:51:09.999 ThaliTest[1799:2946427] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:51:09.999 ThaliTest[1799:2946427] client session: disconnect
2016-03-19 11:51:09.999 ThaliTest[1799:2946427] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:10.000 ThaliTest[1799:2946427] client session: fireConnectCallback: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:51:10.000 ThaliTest[1799:2946427] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-19 11:51:13.011 ThaliTest[1799:2944455] jxcore: connect BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:13.012 ThaliTest[1799:2944455] client session: connect
,2016-03-19 11:51:13.013 ThaliTest[1799:2944455] client session: stateChange:0->1 BFF196CF-9326-4437-A343-829BABDB6CBC:8
,2016-03-19 11:51:13.391 ThaliTest[1799:2946450] client session: not connected BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:51:13.391 ThaliTest[1799:2946450] client session: onLinkFailure: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:51:13.3,92 ThaliTest[1799:2946450] client session: disconnect
2016-03-19 11:51:13.392 ThaliTest[1799:2946450] client session: stateChange:1->0 BFF196CF-9326-4437-A343-829BABDB6CBC:8
2016-03-19 11:51:13.392 ThaliTest[1799:2946450] client session: fireConnectCallb,ack: BFF196CF-9326-4437-A343-829BABDB6CBC
2016-03-19 11:51:13.393 ThaliTest[1799:2946450] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-19 11:51:15.652 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-19 11:51:15.654 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-19 11:51:15.657 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:51:15.658 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:51:15.659 ThaliTest[1799:2944455] multipeer manager: stop client timer
2016-03-19 11:51:15.659 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-19 11:51:16.215 ThaliTest[1799:2944455] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-19 11:51:16.217 ThaliTest[1799:2944455] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-19 11:51:16.218 ThaliTest[1799:2944455] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:16.221 ThaliTest[1799:2944455] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-19 11:51:17.273 ThaliTest[1799:2944455] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-19 11:51:17.274 ThaliTest[1799:2944455] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-19 11:51:17.275 ThaliTest[1799:2944455] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:17.279 ThaliTest[1799:2944455] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-19 11:51:18.265 ThaliTest[1799:2944455] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-19 11:51:18.267 ThaliTest[1799:2944455] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-19 11:51:18.268 ThaliTest[1799:2944455] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:18.271 ThaliTest[1799:2944455] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65342
,2016-03-19 11:51:18.421 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 11:51:18.425 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-19 11:51:18.430 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:51:18.432 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-19 11:51:19.920 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening
,2016-03-19 11:51:19.920 ThaliTest[1799:2944455] THEMultipeerManager stopping peer
,2016-03-19 11:51:19.921 ThaliTest[1799:2944455] jxcore: stopAdvertisingAndListening: success
,2016-03-19 11:51:19.922 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 11:51:19.924 ThaliTest[1799:2944455] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-19 11:51:21.122 ThaliTest[1799:2944455] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-19 11:51:21.123 ThaliTest[1799:2944455] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-19 11:51:21.124 ThaliTest[1799:2944455] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 11:51:21.127 ThaliTest[1799:2944455] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65344
,2016-03-19 11:51:21.451 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,2016-03-19 11:51:21.452 ThaliTest[1799:2944455] multipeer manager: start client restart timer: 0x20199f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:51:21.455 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
,ok 169 no errors
,2016-03-19 11:51:21.459 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 11:51:21.463 ThaliTest[1799:2944455] jxcore: startListeningForAdvertisements: success
ok 170 still no errors
,# setup
,2016-03-19 11:51:22.125 ThaliTest[1799:2944220] client: found new peer: BFF196CF-9326-4437-A343-829BABDB6CBC:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-19 11:51:32.983 ThaliTest[1799:2944220] client: lost peer: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:51:32.984 ThaliTest[1799:2944220] client session: onPeerLost: BFF196CF-9326-4437-A343-829BABDB6CBC
,2016-03-19 11:51:41.453 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:52:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:52:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:52:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:53:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:53:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:53:41.453 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:54:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:54:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:54:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:55:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:55:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:55:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:56:01.453 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:56:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:56:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:57:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:57:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:57:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:58:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:58:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:58:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:59:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:59:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 11:59:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:00:01.453 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:00:21.453 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:00:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:01:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:01:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:01:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:02:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:02:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:02:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:03:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:03:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:03:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:04:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:04:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:04:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:05:01.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:05:21.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:05:41.454 ThaliTest[1799:2944220] multipeer manager: restart client
,2016-03-19 12:06:01.453 ThaliTest[1799:2944220] multipeer manager: restart client

```
