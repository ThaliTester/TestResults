#### Test 636801181df08af_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BEE8F0B7-9988-42BD-A721-81C601E2A56D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BEE8F0B7-9988-42BD-A721-81C601E2A56D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/636801181df08af/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54591"
,(lldb)     command script import "/tmp/BEE8F0B7-9988-42BD-A721-81C601E2A56D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-22 09:05:23.662 ThaliTest[1979:3397541] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C256668-F87B-45BC-92E6-3A2767C08839/Library/Cookies/Cookies.binarycookies
,2016-03-22 09:05:24.075 ThaliTest[1979:3397541] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-22 09:05:24.077 ThaliTest[1979:3397541] Multi-tasking -> Device: YES, App: YES
,2016-03-22 09:05:24.106 ThaliTest[1979:3397541] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-22 09:05:26.028 ThaliTest[1979:3397541] Using UIWebView
,2016-03-22 09:05:26.036 ThaliTest[1979:3397541] [CDVTimer][handleopenurl] 0.425994ms
,2016-03-22 09:05:26.045 ThaliTest[1979:3397541] [CDVTimer][intentandnavigationfilter] 8.083999ms
2016-03-22 09:05:26.046 ThaliTest[1979:3397541] [CDVTimer][gesturehandler] 0.362039ms
2016-03-22 09:05:26.046 ThaliTest[1979:3397541] [CDVTimer][TotalPluginStartup] 10.713995ms
,2016-03-22 09:05:33.837 ThaliTest[1979:3397541] Resetting plugins due to page load.
,2016-03-22 09:05:37.850 ThaliTest[1979:3397541] Finished load of: file:///var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/index.html
,2016-03-22 09:05:38.114 ThaliTest[1979:3397541] JXcore Cordova plugin initializing
,2016-03-22 09:05:38.115 ThaliTest[1979:3397746] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-22 09:05:47.068 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:05:47.069 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:05:47.070 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:05:47.072 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6CB2D99F-2814-45D0-82C5-FEBD8E196C91/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-22 09:05:54.062 ThaliTest[1979:3397541] THREAD WARNING: ['JXcore'] took '6616.141113' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50507
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50509
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
,DEBUG createNativeListener: listening 50512
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
,DEBUG createNativeListener: listening 50516
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
,DEBUG createNativeListener: listening 50521
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
,DEBUG createNativeListener: listening 50525
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
,DEBUG createNativeListener: listening 50529
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
,DEBUG createNativeListener: listening 50533
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
,DEBUG createNativeListener: listening 50537
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
,DEBUG createNativeListener: listening 50589
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
,DEBUG createNativeListener: listening 50593
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
,# 21. can pass data in setup
,# teardown
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 80 specific error should be returned
,# setup
,ok 81 error should be null
,ok 82 error should be null
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 83 specific error should be returned
,# setup
,ok 84 error should be null
,ok 85 error should be null
,# 24. should be able to call #stopListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50605
,2016-03-22 09:07:40.774 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:40.777 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,2016-03-22 09:07:40.785 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:40.787 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,# setup
,2016-03-22 09:07:40.958 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:40.958 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:40.959 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 09:07:40.960 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:40.962 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# 25. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50607
,2016-03-22 09:07:41.326 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
,2016-03-22 09:07:41.330 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:41.333 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,2016-03-22 09:07:41.358 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:41.363 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,# setup
,2016-03-22 09:07:41.744 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:41.744 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:41.745 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:07:41.747 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
2016-03-22 09:07:41.748 ThaliTest[1979:3397746] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:41.750 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 96 error should be null
,ok 97 error should be null
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50609
,2016-03-22 09:07:42.329 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 09:07:42.330 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:1
,2016-03-22 09:07:42.333 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
2016-03-22 09:07:42.334 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:1
2016-03-22 09:07:42.334 ,ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
,ok 98 error should be null
ok 99 error should be null
,2016-03-22 09:07:42.368 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:42.368 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:42.370 ThaliTest[1979:3397746] multipeer manager: stop client ti,mer
2016-03-22 09:07:42.371 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:2
2016-03-22 09:07:42.373 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
2016-03-22 09:07:42.373 ThaliTest[1979:,3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:2
2016-03-22 09:07:42.374 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,# setup
,2016-03-22 09:07:42.795 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:07:42.795 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:42.797 ThaliTest[1979:3397746] multipeer manager: stop client timer
2016-03-22 09:07:42.797 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: su,ccess
2016-03-22 09:07:42.798 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:42.800 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 102 error should be null
,ok 103 error should be null
,# 27. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50614
,2016-03-22 09:07:43.652 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:43.652 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:07:43.653 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,ok 104 error should be null
,ok 105 error should be null
,2016-03-22 09:07:43.661 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:43.662 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:43.662 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: suc,cess
,ok 106 error should be null
,ok 107 error should be null
,# setup
,2016-03-22 09:07:43.782 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:43.782 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:43.782 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:07:43.783 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:43.787 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 108 error should be null
,ok 109 error should be null
,# 28. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50616
,ok 110 first call should succeed
,ok 111 first call should succeed
,ok 112 specific error should be returned
,# setup
,2016-03-22 09:07:44.343 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:44.344 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:44.344 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-22 09:07:44.345 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-22 09:07:44.347 ThaliTest[1979,:3397746] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50618
,2016-03-22 09:07:45.221 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
2016-03-22 09:07:45.222 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:45.225 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,2016-03-22 09:07:45.248 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:45.249 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:3
2016-03-22 09:07:45.250 ThaliTest[1979:3397746] THEMultipee,rManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:3
2016-03-22 09:07:45.251 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
,ok 115 called only once
,ok 116 discovery state matches
,ok 117 advertising state matches
,# setup
,2016-03-22 09:07:45.435 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:45.436 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:07:45.437 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:07:45.438 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
2016-03-22 09:07:45.440 ThaliTest[1979:3397746] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:45.443 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 118 error should be null
,ok 119 error should be null
,# 30. does not send duplicate availability changes
,# teardown
,ok 120 should be called once
,ok 121 should not have been called more than once
,# setup
,ok 122 error should be null
,ok 123 error should be null
,# 31. can get the network status
,# teardown
,ok 124 network status should have certain non-empty properties
,# setup
,ok 125 error should be null
,ok 126 error should be null
,# 32. wifi peer is marked unavailable if announcements stop
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 127 host address should match
,ok 128 port should match
,ok 129 host address should be null
,ok 130 port should should be null
,# setup
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 131 error should be null
,ok 132 error should be null
,# 33. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-22 09:07:51.323 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
2016-03-22 09:07:51.323 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:51.326 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
ok 133 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:51.330 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,2016-03-22 09:07:51.338 ThaliTest[1979:3397746] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:51.347 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
ok 134 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-22 09:07:51.579 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:51.582 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:51.586 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:51.586 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:51.586 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: suc,cess
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-22 09:07:51.804 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
2016-03-22 09:07:51.805 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:51.809 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
ok 137 Can call startListeningForAdvertisements without error
2016-03-22 09:07:51.813 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
DEBUG ,thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:07:51.816 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-22 09:07:52.339 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
2016-03-22 09:07:52.340 ThaliTest[1979:3397746] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:52.343 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
ok 139 Should be able to call stopListeningForAdvertisments in teardown
2016-03-22 09:07:52.346 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2,016-03-22 09:07:52.346 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:52.347 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-22 09:07:52.786 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:52.787 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:4
2016-03-22 09:07:52.788 ThaliTest[1979:3397746] multipeer m,anager: start client restart timer: 0x17e91b60
2016-03-22 09:07:52.788 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:4
2016-03-22 09:07:52.789 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
,ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 09:07:52.792 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:07:52.793 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:52.794 ThaliTest[1979:3397746] multipeer manager: stop client timer
2016-03-22 09:07:52.794 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
ok 142 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-22 09:07:53.155 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:07:53.157 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:53.160 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:53.161 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:53.161 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: suc,cess
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-22 09:07:53.339 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:53.339 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:5
2016-03-22 09:07:53.340 ThaliTest[1979:3397746] multipeer m,anager: start client restart timer: 0x17e91b60
2016-03-22 09:07:53.341 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:5
2016-03-22 09:07:53.341 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
,ok 145 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 09:07:53.346 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:53.346 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:53.347 ThaliTest[1979:3397746] multipeer manager: stop client ti,mer
2016-03-22 09:07:53.348 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:6
2016-03-22 09:07:53.349 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
2016-03-22 09:07:53.349 ThaliTest[1979:,3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:6
2016-03-22 09:07:53.349 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
ok 146 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-22 09:07:54.423 ThaliTest[1979:3397541] client: found new peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:07:54.743 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:07:54.746 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 147 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:54.749 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:54.749 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:54.750 ThaliTest[1979:3397746] multipeer manager: stop client timer
20,16-03-22 09:07:54.750 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
ok 148 Should be able to call stopAdvertisingAndListening in teardown
,# 37. peerAvailabilityChange is called
,# teardown
,2016-03-22 09:07:55.326 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:55.326 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:07:55.327 ThaliTest[1979:3397746] multipeer m,anager: start client restart timer: 0x17e91b60
2016-03-22 09:07:55.327 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:7
2016-03-22 09:07:55.328 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 149 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-22 09:07:55.331 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 09:07:55.333 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 150 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:56.124 ThaliTest[1979:3397541] client: found new peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
ok 151 peers must be an array
ok 152 peers must not be zero-length
ok 153 peer must have peerIdentifier
ok 154 peerIdentifier must be a string
,ok 155 peer must have peerAvailable
,ok 156 peer must have pleaseConnect
,# setup
,2016-03-22 09:07:56.443 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:07:56.446 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 157 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:07:56.449 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:07:56.450 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:07:56.450 ThaliTest[1979:3397746] multipeer manager: stop client timer
20,16-03-22 09:07:56.451 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
ok 158 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can connect to a remote peer
,# teardown
,2016-03-22 09:07:56.881 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:07:56.882 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:07:56.883 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
,2016-03-22 09:07:56.885 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:8
,2016-03-22 09:07:56.886 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
,ok 159 Can call startUpdateAdvertisingAndListening without error
2016-03-22 09:07:56.889 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-22 09:07:56.891 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
ok 160 Can call startListeningForAdvertisements without error
,2016-03-22 09:07:57.639 ThaliTest[1979:3397541] client: found new peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6","pleaseConnect":0}]
,2016-03-22 09:07:57.644 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:07:57.645 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:07:57.645 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:07:59.304 ThaliTest[1979:3398024] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:07:59.306 ThaliTest[1979:3398024] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:07:59.3,06 ThaliTest[1979:3398024] client session: disconnect
2016-03-22 09:07:59.307 ThaliTest[1979:3398024] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:07:59.307 ThaliTest[1979:3398024] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:07:59.308 ThaliTest[1979:3398024] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 09:07:59.563 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:07:59.563 ThaliTest[1979:3397541] server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:8 != E9CB2080-C667-4537-8057-9C336E6593A8:7)
,2016-03-22 09:08:02.316 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:02.317 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:02.317 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:02.416 ThaliTest[1979:3398024] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:02.416 ThaliTest[1979:3398024] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:02.4,18 ThaliTest[1979:3398024] client session: disconnect
2016-03-22 09:08:02.418 ThaliTest[1979:3398024] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:02.419 ThaliTest[1979:3398024] client session: fireConnectCallb,ack: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:02.419 ThaliTest[1979:3398024] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-22 09:08:05.431 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:05.432 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:05.432 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:05.645 ThaliTest[1979:3398050] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:05.646 ThaliTest[1979:3398050] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:08:05.646 ThaliTest[1979:3398050] client session: disconnect
,2016-03-22 09:08:05.647 ThaliTest[1979:3398050] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:05.649 ThaliTest[1979:3398050] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 0,9:08:05.649 ThaliTest[1979:3398050] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 09:08:08.659 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:08.659 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:08.660 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:08.833 ThaliTest[1979:3398049] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:08.833 ThaliTest[1979:3398049] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:08.8,33 ThaliTest[1979:3398049] client session: disconnect
2016-03-22 09:08:08.834 ThaliTest[1979:3398049] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:08.838 ThaliTest[1979:3398049] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:08.838 ThaliTest[1979:3398049] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 09:08:11.823 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:08:11.824 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:08:11.824 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:8 != E9CB2080-C667-4537-8057-9C336E6593A8:7)
,2016-03-22 09:08:11.849 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:11.850 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:11.851 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:12.015 ThaliTest[1979:3398152] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:12.015 ThaliTest[1979:3398152] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:12.016 ThaliTest[1979:3398152] client session: disconnect
,2016-03-22 09:08:12.017 ThaliTest[1979:3398152] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:12.020 ThaliTest[1979:3398152] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:12.020 ThaliTest[1979:3398152] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 09:08:15.028 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:15.029 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:15.029 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:15.485 ThaliTest[1979:3398024] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:15.486 ThaliTest[1979:3398024] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:15.4,86 ThaliTest[1979:3398024] client session: disconnect
2016-03-22 09:08:15.486 ThaliTest[1979:3398024] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
,2016-03-22 09:08:15.488 ThaliTest[1979:3398024] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:08:15.488 ThaliTest[1979:3398024] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 09:08:16.886 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:08:16.914 ThaliTest[1979:3397541] client: found updated peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8","pleaseConnect":0}]
,2016-03-22 09:08:18.506 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:18.507 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:18.507 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:18.644 ThaliTest[1979:3398024] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:08:18.645 ThaliTest[1979:3398024] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:18.6,45 ThaliTest[1979:3398024] client session: disconnect
2016-03-22 09:08:18.646 ThaliTest[1979:3398024] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:08:18.646 ThaliTest[1979:3398024] client session: fireConnectCallb,ack: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:18.647 ThaliTest[1979:3398024] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-03-22 09:08:21.654 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:21.655 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:21.655 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:21.774 ThaliTest[1979:3398052] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:08:21.775 ThaliTest[1979:3398052] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:21.7,76 ThaliTest[1979:3398052] client session: disconnect
2016-03-22 09:08:21.776 ThaliTest[1979:3398052] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:21.780 ThaliTest[1979:3398052] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:08:21.781 ThaliTest[1979:3398052] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-22 09:08:24.637 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:08:24.638 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:08:24.638 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:8 != E9CB2080-C667-4537-8057-9C336E6593A8:7)
,2016-03-22 09:08:24.791 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:24.792 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:24.792 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:24.919 ThaliTest[1979:3398152] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:08:24.920 ThaliTest[1979:3398152] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:24.9,20 ThaliTest[1979:3398152] client session: disconnect
,2016-03-22 09:08:24.921 ThaliTest[1979:3398152] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:24.925 ThaliTest[1979:3398152] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:08:24.926 ThaliTest[1979:3398152] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 09:08:27.935 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:6
2016-03-22 09:08:27.936 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:08:27.936 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:28.261 ThaliTest[1979:3398052] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:08:28.261 ThaliTest[1979:3398052] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:28.262 ThaliTest[1979:3398052] client session: disconnect
,2016-03-22 09:08:28.262 ThaliTest[1979:3398052] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:28.268 ThaliTest[1979:3398052] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:08:28.268 ThaliTest[1979:3398052] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
WARN testThaliMobileNative: Too many connect retries!
,not ok 161 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-22 09:08:36.886 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:08:36.911 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:08:56.886 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:08:56.923 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:05.430 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:09:05.433 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 162 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:09:05.437 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:09:05.437 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:09:05.438 ThaliTest[1979:3397746] multipeer manager: stop client timer
20,16-03-22 09:09:05.439 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
ok 163 Should be able to call stopAdvertisingAndListening in teardown
,# 39. Can shift large amounts of data
,# teardown
,2016-03-22 09:09:05.776 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:09:05.776 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:09:05.777 ThaliTest[1979:3397746] multipeer m,anager: start client restart timer: 0x17e91b60
2016-03-22 09:09:05.778 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:9
2016-03-22 09:09:05.778 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
ok 164 Can call startUpdateAdvertisingAndListening without error
,2016-03-22 09:09:05.781 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-22 09:09:05.783 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 165 Can call startListeningForAdvertisements without error
,2016-03-22 09:09:06.582 ThaliTest[1979:3397541] client: found new peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:06.586 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:06.587 ThaliTest[1979:3397746] client session: connect
,2016-03-22 09:09:06.589 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:07.905 ThaliTest[1979:3398200] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:07.906 ThaliTest[1979:3398200] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:07.9,06 ThaliTest[1979:3398200] client session: disconnect
2016-03-22 09:09:07.906 ThaliTest[1979:3398200] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:07.911 ThaliTest[1979:3398200] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:09:07.911 ThaliTest[1979:3398200] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-22 09:09:08.427 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:09:08.428 ThaliTest[1979:3397541] server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:09:10.923 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:10.924 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:10.924 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:11.629 ThaliTest[1979:3398256] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:11.630 ThaliTest[1979:3398256] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:11.6,30 ThaliTest[1979:3398256] client session: disconnect
2016-03-22 09:09:11.632 ThaliTest[1979:3398256] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:11.633 ThaliTest[1979:3398256] client session: fireConnectCallb,ack: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:11.633 ThaliTest[1979:3398256] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 8
,2016-03-22 09:09:14.640 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:14.641 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:14.641 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:14.778 ThaliTest[1979:3398200] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:14.782 ThaliTest[1979:3398200] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:09:14.783 ThaliTest[1979:3398200] client session: disconnect
,2016-03-22 09:09:14.785 ThaliTest[1979:3398200] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:14.789 ThaliTest[1979:3398200] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:14.790 ThaliTest[1979:3398200] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-22 09:09:17.805 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:17.806 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:17.806 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:17.991 ThaliTest[1979:3398256] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:17.992 ThaliTest[1979:3398256] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:17.993 ThaliTest[1979:3398256] client session: disconnect
2016-03-22 09:09:17.993 ThaliTest[1979:3398256] client session:, stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:17.994 ThaliTest[1979:3398256] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:17.995 ThaliTest[1979:3398256] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-22 09:09:20.089 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:09:20.090 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:09:20.090 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:09:21.007 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:21.008 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:21.008 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:21.225 ThaliTest[1979:3398256] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:21.225 ThaliTest[1979:3398256] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:21.2,26 ThaliTest[1979:3398256] client session: disconnect
2016-03-22 09:09:21.227 ThaliTest[1979:3398256] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:21.229 ThaliTest[1979:3398256] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:21.230 ThaliTest[1979:3398256] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returne,d an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-22 09:09:24.238 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:24.239 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:24.239 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:24.684 ThaliTest[1979:3398278] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:24.685 ThaliTest[1979:3398278] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:24.6,85 ThaliTest[1979:3398278] client session: disconnect
,2016-03-22 09:09:24.685 ThaliTest[1979:3398278] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:24.690 ThaliTest[1979:3398278] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:24.690 ThaliTest[1979:3398278] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-22 09:09:25.779 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:09:25.804 ThaliTest[1979:3397541] client: found updated peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:27.897 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:27.897 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:27.897 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:28.416 ThaliTest[1979:3398278] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:28.417 ThaliTest[1979:3398278] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:28.4,17 ThaliTest[1979:3398278] client session: disconnect
2016-03-22 09:09:28.418 ThaliTest[1979:3398278] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:28.419 ThaliTest[1979:3398278] client session: fireConnectCallb,ack: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:28.420 ThaliTest[1979:3398278] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 3
,2016-03-22 09:09:31.435 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:31.436 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:31.436 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:31.565 ThaliTest[1979:3398052] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:31.565 ThaliTest[1979:3398052] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:31.5,66 ThaliTest[1979:3398052] client session: disconnect
2016-03-22 09:09:31.566 ThaliTest[1979:3398052] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:31.568 ThaliTest[1979:3398052] client session: fireConnectCallb,ack: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:31.569 ThaliTest[1979:3398052] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 2
,2016-03-22 09:09:32.933 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:09:32.934 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
,2016-03-22 09:09:32.936 ThaliTest[1979:3397541] server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:09:34.581 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
2016-03-22 09:09:34.582 ThaliTest[1979:3397746] client session: connect
2016-03-22 09:09:34.583 ThaliTest[1979:3397746] client session: stateChange:0->,1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:34.699 ThaliTest[1979:3398052] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:34.700 ThaliTest[1979:3398052] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:34.7,00 ThaliTest[1979:3398052] client session: disconnect
2016-03-22 09:09:34.700 ThaliTest[1979:3398052] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:34.701 ThaliTest[1979:3398052] client session: fireConnectCallb,ack: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:34.701 ThaliTest[1979:3398052] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-22 09:09:37.710 ThaliTest[1979:3397746] jxcore: connect 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:8
,2016-03-22 09:09:37.712 ThaliTest[1979:3397746] client session: connect
,2016-03-22 09:09:37.713 ThaliTest[1979:3397746] client session: stateChange:0->1 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:37.855 ThaliTest[1979:3398279] client session: not connected 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
2016-03-22 09:09:37.856 ThaliTest[1979:3398279] client session: onLinkFailure: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
2016-03-22 09:09:37.8,56 ThaliTest[1979:3398279] client session: disconnect
,2016-03-22 09:09:37.856 ThaliTest[1979:3398279] client session: stateChange:1->0 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:37.860 ThaliTest[1979:3398279] client session: fireConnectCallback: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B
,2016-03-22 09:09:37.861 ThaliTest[1979:3398279] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 166 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-22 09:09:45.778 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:09:45.801 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:09:46.236 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:09:46.236 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:09:46.237 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:09:59.542 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:09:59.542 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:09:59.543 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:10:05.779 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:10:05.804 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:10:13.572 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:10:13.573 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:10:13.573 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:10:25.171 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:10:25.171 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:10:25.172 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:10:25.779 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:10:25.802 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:10:38.134 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:10:38.134 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:10:38.135 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:10:45.779 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:10:45.802 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:10:52.382 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:10:52.383 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:10:52.383 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:11:04.343 ThaliTest[1979:3397541] multipeer session: reset timer
2016-03-22 09:11:04.344 ThaliTest[1979:3397541] server: disconnecting to refresh session (1DD4AA51-FDA9-49C8-90F1-2FE034BF189B)
2016-03-22 09:11:04.344 ThaliTest[1979:3397541], server: rejecting invitation from 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B due to previous generation (E9CB2080-C667-4537-8057-9C336E6593A8:9 != E9CB2080-C667-4537-8057-9C336E6593A8:8)
,2016-03-22 09:11:05.778 ThaliTest[1979:3397541] multipeer manager: restart client
,2016-03-22 09:11:05.801 ThaliTest[1979:3397541] client: found existing peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
,2016-03-22 09:11:13.935 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-22 09:11:13.938 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 167 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-22 09:11:13.942 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:13.943 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:11:13.948 ThaliTest[1979:3397746] multipeer manager: stop client timer
2016-03-22 09:11:13.952 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,ok 168 Should be able to call stopAdvertisingAndListening in teardown
,# 40. #startListeningForAdvertisements should fail if start not called
,2016-03-22 09:11:14.072 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:14.073 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:14.074 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:14.079 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 169 specific error should be returned
,# setup
,# 41. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-22 09:11:14.642 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:14.643 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:14.644 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:14.648 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 170 specific error should be returned
,# setup
,# 42. should be able to call #stopListeningForAdvertisements many times
,2016-03-22 09:11:15.430 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:15.431 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:15.432 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:15.437 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50660
,2016-03-22 09:11:15.562 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:15.566 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 171 no errors
,2016-03-22 09:11:15.571 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:15.575 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,ok 172 still no errors
,# setup
,2016-03-22 09:11:15.705 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:15.706 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:11:15.706 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
2016-03-22 09:11:15.707 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:15.712 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startListeningForAdvertisements many times
,2016-03-22 09:11:15.964 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:15.966 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:15.967 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:15.971 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50662
,2016-03-22 09:11:16.133 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
2016-03-22 09:11:16.134 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:11:16.145 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 173 no errors
,2016-03-22 09:11:16.154 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-22 09:11:16.160 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success
,ok 174 still no errors
,# setup
,2016-03-22 09:11:16.259 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:16.260 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:11:16.265 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:11:16.267 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,2016-03-22 09:11:16.270 ThaliTest[1979:3397746] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:16.278 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-22 09:11:16.605 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:16.607 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:16.607 ThaliTest[1979:3,397746] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:16.610 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50664
,2016-03-22 09:11:16.747 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
2016-03-22 09:11:16.748 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-8057-9C336E6593A8:10
,2016-03-22 09:11:16.751 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
2016-03-22 09:11:16.751 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:10
2016-03-22 09:11:16.751, ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
ok 175 no errors
,2016-03-22 09:11:16.755 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening
,2016-03-22 09:11:16.756 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:11:16.757 ThaliTest[1979:3397746] multipeer manager: stop client timer
2016-03-22 09:11:16.758 ThaliTest[1979:3397746] server: starting E9CB2080-C667-4537-805,7-9C336E6593A8:11
2016-03-22 09:11:16.758 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
2016-03-22 09:11:16.759 ThaliTest[1979:3397746] THEMultipeerManager initialized peer E9CB2080-C667-4537-8057-9C336E6593A8:11
2016,-03-22 09:11:16.759 ThaliTest[1979:3397746] jxcore: startUpdateAdvertisingAndListening: success
ok 176 still no errors
# setup
,2016-03-22 09:11:17.030 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:17.032 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:11:17.037 ThaliTest[1979:3397746] multipeer manager: stop client timer
,2016-03-22 09:11:17.040 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,2016-03-22 09:11:17.042 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:17.047 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,# 45. should be able to call #stopAdvertisingAndListening many times
,2016-03-22 09:11:17.272 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:11:17.275 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 09:11:17.277 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:17.281 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50668
,2016-03-22 09:11:17.742 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:17.744 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:11:17.745 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,ok 177 no errors
,2016-03-22 09:11:17.750 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
,2016-03-22 09:11:17.751 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
,2016-03-22 09:11:17.752 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
,ok 178 still no errors
,# setup
,2016-03-22 09:11:18.152 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening
2016-03-22 09:11:18.153 ThaliTest[1979:3397746] THEMultipeerManager stopping peer
2016-03-22 09:11:18.153 ThaliTest[1979:3397746] jxcore: stopAdvertisingAndListening: success
2016-03-22 09:11:18.154 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-22 09:11:18.157 ThaliTest[1979:3397746] jxcore: stopListeningForAdvertisements: success
,# 46. can get the network status before starting
,2016-03-22 09:11:18.276 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:18.277 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:18.277 ThaliTest[1979:3,397746] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:18.282 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 179 network status should have certain non-empty properties
,# setup
,# 47. error returned with bad router
,2016-03-22 09:11:23.222 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-22 09:11:23.223 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-22 09:11:23.224 ThaliTest[1979:3,397746] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:23.227 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 180 specific error expected
,# setup
,# 48. all services are stopped when we call stop
,2016-03-22 09:11:23.554 ThaliTest[1979:3397746] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-22 09:11:23.556 ThaliTest[1979:3397746] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-22 09:11:23.559 ThaliTest[1979:3397746] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-22 09:11:23.563 ThaliTest[1979:3397746] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50670
,2016-03-22 09:11:23.818 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements
,2016-03-22 09:11:23.821 ThaliTest[1979:3397746] multipeer manager: start client restart timer: 0x17e91b60
,2016-03-22 09:11:23.840 ThaliTest[1979:3397541] client: found new peer: 1DD4AA51-FDA9-49C8-90F1-2FE034BF189B:9
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-22 09:11:23.8,42 ThaliTest[1979:3397746] jxcore: startListeningForAdvertisements: success

```
