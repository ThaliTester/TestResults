#### Test 625481245382a4d_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2D05D57C-2D0E-42C7-A4FA-CF486C8A272E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/2D05D57C-2D0E-42C7-A4FA-CF486C8A272E/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481245382a4d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53213"
,(lldb)     command script import "/tmp/2D05D57C-2D0E-42C7-A4FA-CF486C8A272E/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-20 12:38:25.952 ThaliTest[1395:3259393] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3DE0D278-5E09-4DA1-896F-57C407BD70D2/Library/Cookies/Cookies.binarycookies
,2016-03-20 12:38:26.066 ThaliTest[1395:3259393] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-20 12:38:26.068 ThaliTest[1395:3259393] Multi-tasking -> Device: YES, App: YES
,2016-03-20 12:38:26.085 ThaliTest[1395:3259393] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-20 12:38:28.237 ThaliTest[1395:3259393] Using UIWebView
,2016-03-20 12:38:28.242 ThaliTest[1395:3259393] [CDVTimer][handleopenurl] 0.371993ms
,2016-03-20 12:38:28.247 ThaliTest[1395:3259393] [CDVTimer][intentandnavigationfilter] 5.025029ms
2016-03-20 12:38:28.247 ThaliTest[1395:3259393] [CDVTimer][gesturehandler] 0.257969ms
2016-03-20 12:38:28.248 ThaliTest[1395:3259393] [CDVTimer][TotalPluginStartup] 6.696999ms
,2016-03-20 12:38:36.563 ThaliTest[1395:3259393] Resetting plugins due to page load.
,2016-03-20 12:38:40.507 ThaliTest[1395:3259393] Finished load of: file:///var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/index.html
,2016-03-20 12:38:40.719 ThaliTest[1395:3259393] JXcore Cordova plugin initializing
,2016-03-20 12:38:40.721 ThaliTest[1395:3259594] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-20 12:38:57.309 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:38:57.310 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:38:57.310 ThaliTest[1395:3259594] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:38:57.313 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/50303472-CD37-4D0E-87A5-06636670F1C8/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-20 12:39:10.793 ThaliTest[1395:3259393] THREAD WARNING: ['JXcore'] took '12782.381836' ms. Plugin should use a background thread.
,2016-03-20 12:39:10.796 ThaliTest[1395:3259538] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMod,e
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65371
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65373
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
,DEBUG createNativeListener: listening 65377
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
,DEBUG createNativeListener: listening 65381
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
,DEBUG createNativeListener: listening 65386
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
,DEBUG createNativeListener: listening 65390
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
,DEBUG createNativeListener: listening 65394
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
,DEBUG createNativeListener: listening 65398
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
,DEBUG createNativeListener: listening 65402
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: listening 65454
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
ok 34 server should be open
,ok 35 incoming has been removed
ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65458
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
ok 56 thirdPromise testValue
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
,DEBUG createNativeListener: listening 65470
,2016-03-20 12:43:12.913 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:12.915 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-20 12:43:12.919 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:12.920 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-20 12:43:13.013 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:13.013 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:13.013 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:43:13.014 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:13.015 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 65472
,2016-03-20 12:43:13.389 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
,2016-03-20 12:43:13.392 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:13.395 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
ok 89 error should be null
2016-03-20 12:43:13.412 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:13.414 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
ok 91 error should be null
,# setup
,2016-03-20 12:43:13.722 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:13.722 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:13.722 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:43:13.722 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
2016-03-20 12:43:13.723 ThaliTest[1395:3259594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:13.724 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65474
,2016-03-20 12:43:14.363 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:14.364 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:1
2016-03-20 12:43:14.365 ThaliTest[1395:3259594] multipeer m,anager: start client restart timer: 0x156d0a80
2016-03-20 12:43:14.365 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:1
2016-03-20 12:43:14.365 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-20 12:43:14.404 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:14.405 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:14.405 ThaliTest[1395:3259594] multipeer manager: stop client ti,mer
2016-03-20 12:43:14.405 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:2
2016-03-20 12:43:14.406 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
2016-03-20 12:43:14.407 ThaliTest[1395:,3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:2
,2016-03-20 12:43:14.412 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-20 12:43:14.956 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:14.956 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:14.957 ThaliTest[1395:3259594] multipeer manager: stop client timer
2016-03-20 12:43:14.957 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
2016-03-20 12:43:14.957 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:14.958 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65479
,2016-03-20 12:43:15.836 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:15.837 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:15.837 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-20 12:43:15.840 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:15.841 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:15.841 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-20 12:43:15.982 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:15.982 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:15.983 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:43:15.983 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:15.984 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65481
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-20 12:43:18.001 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:18.002 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:18.002 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:43:18.002 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:18.003 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65483
,2016-03-20 12:43:18.441 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
2016-03-20 12:43:18.442 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-20 12:43:18.443 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,2016-03-20 12:43:18.462 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:18.462 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:3
2016-03-20 12:43:18.463 ThaliTest[1395:3259594] THEMultipee,rManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:3
2016-03-20 12:43:18.463 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-20 12:43:18.623 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:18.623 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:18.623 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:43:18.624 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
2016-03-20 12:43:18.624 ThaliTest[1395:3259594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:18.625 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-20 12:43:24.570 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
2016-03-20 12:43:24.570 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:43:24.571 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
2016-03-20 12:43:24.573 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
,2016-03-20 12:43:24.573 ThaliTest[1395:3259594] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:43:24.575 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdv,ertisements without error
# setup
,2016-03-20 12:43:24.824 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:24.825 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:24.827 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:24.827 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:24.827 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-20 12:43:25.357 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
2016-03-20 12:43:25.358 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:43:25.359 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
ok 133 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:25.360 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:43:25.361 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
# setup
,2016-03-20 12:43:25.540 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
2016-03-20 12:43:25.540 ThaliTest[1395:3259594] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:25.542 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:25.545 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:25.545 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:25.545 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-20 12:43:28.446 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:28.446 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:4
2016-03-20 12:43:28.447 ThaliTest[1395:3259594] multipeer m,anager: start client restart timer: 0x156d0a80
2016-03-20 12:43:28.447 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:4
2016-03-20 12:43:28.447 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-20 12:43:28.449 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:28.449 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016,-03-20 12:43:28.449 ThaliTest[1395:3259594] multipeer manager: stop client timer
2016-03-20 12:43:28.449 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-20 12:43:28.643 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:43:28.644 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:28.646 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:28.646 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:28.646 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-20 12:43:29.161 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:29.161 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:5
2016-03-20 12:43:29.162 ThaliTest[1395:3259594] multipeer m,anager: start client restart timer: 0x156d0a80
2016-03-20 12:43:29.162 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:5
2016-03-20 12:43:29.162 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-20 12:43:29.164 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:29.164 ThaliTest[1395:3259594] THEMultipeerManager stopping pee,r
2016-03-20 12:43:29.164 ThaliTest[1395:3259594] multipeer manager: stop client timer
2016-03-20 12:43:29.165 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:6
2016-03-20 12:43:29.165 ThaliTest[1395:3259594] multipeer mana,ger: start client restart timer: 0x156d0a80
2016-03-20 12:43:29.170 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:6
2016-03-20 12:43:29.171 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-20 12:43:29.489 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:43:29.491 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:29.493 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:29.493 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:29.493 ThaliTest[1395:3259594] multipeer manager: stop client timer
20,16-03-20 12:43:29.493 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-20 12:43:30.265 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:30.265 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:7
2016-03-20 12:43:30.266 ThaliTest[1395:3259594] multipeer m,anager: start client restart timer: 0x156d0a80
2016-03-20 12:43:30.266 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:7
2016-03-20 12:43:30.266 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-20 12:43:30.268 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-20 12:43:30.270 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:31.454 ThaliTest[1395:3259393] client: found new peer: F82F884A-9394-418C-8996-A62FEDB8DD77:7
ok 147 peers must be an array
ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-20 12:43:32.931 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:43:32.933 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:43:32.934 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:43:32.935 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:43:32.935 ThaliTest[1395:3259594] multipeer manager: stop client timer
20,16-03-20 12:43:32.935 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-20 12:43:33.448 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:43:33.448 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:43:33.449 ThaliTest[1395:3259594] multipeer m,anager: start client restart timer: 0x156d0a80
2016-03-20 12:43:33.449 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:8
2016-03-20 12:43:33.449 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-20 12:43:33.451 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-20 12:43:33.452 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-20 12:43:35.600 ThaliTest[1395:3259393] client: found new peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"F82F884A-9394-418C-8996-A62FEDB8DD77:8","pleaseConnect":0}]
,2016-03-20 12:43:35.603 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:43:35.604 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:43:35.604 ThaliTest[1395:3259594] client session: reverseConn,ect
2016-03-20 12:43:35.604 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:43:35.887 ThaliTest[1395:3260085] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:43:35.887 ThaliTest[1395:3260085] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:43:35.8,87 ThaliTest[1395:3260085] client session: disconnect
2016-03-20 12:43:35.887 ThaliTest[1395:3260085] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:43:35.889 ThaliTest[1395:3260085] client session: no connect callback (server initiated)
,2016-03-20 12:43:35.893 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:35.894 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F6,33DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:39.314 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:39.314 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:39.314 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:42.483 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:42.484 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:42.484 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:45.605 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-20 12:43:45.681 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:45.681 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:45.681 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:48.614 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:43:48.615 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:43:48.615 ThaliTest[1395:3259594] client session: reverseConn,ect
2016-03-20 12:43:48.616 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:43:49.266 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:49.266 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:49.266 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:49.283 ThaliTest[1395:3260127] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:43:49.284 ThaliTest[1395:3260127] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:43:49.2,84 ThaliTest[1395:3260127] client session: disconnect
2016-03-20 12:43:49.285 ThaliTest[1395:3260127] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:43:49.285 ThaliTest[1395:3260127] client session: no connect callback (server initiated)
,2016-03-20 12:43:52.380 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:52.380 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:52.380 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:53.449 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:43:53.464 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:43:55.557 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:55.558 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:55.558 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:43:58.617 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-20 12:43:58.699 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:43:58.700 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:43:58.700 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:44:01.632 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:01.633 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:44:01.633 ThaliTest[1395:3259594] client session: reverseConn,ect
2016-03-20 12:44:01.634 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:01.852 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:44:01.853 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:44:01.853 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:44:01.875 ThaliTest[1395:3260127] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:01.875 ThaliTest[1395:3260127] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:44:01.8,75 ThaliTest[1395:3260127] client session: disconnect
2016-03-20 12:44:01.875 ThaliTest[1395:3260127] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:01.876 ThaliTest[1395:3260127] client session: no connect callback (server initiated)
,2016-03-20 12:44:04.969 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:44:04.969 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:44:04.969 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:8 != 5A342616-0ECA-48AE-829A-448F633DC8C8:7)
,2016-03-20 12:44:11.634 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-20 12:44:13.449 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:44:13.463 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:14.646 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:14.647 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:44:14.648 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:44:14.648 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:15.914 ThaliTest[1395:3260127] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:15.914 ThaliTest[1395:3260127] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
,2016-03-20 12:44:15.914 ThaliTest[1395:3260127] client session: disconnect
2016-03-20 12:44:15.915 ThaliTest[1395:3260127] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:15.916 ThaliTest[1395:3260127] client session: no connect callback (server initiated)
,2016-03-20 12:44:24.648 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-20 12:44:27.663 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:27.664 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:44:27.664 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:44:27.665 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:29.019 ThaliTest[1395:3260294] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:29.019 ThaliTest[1395:3260294] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:44:29.019 ThaliTest[1395:3260294] client session: disconnect
2016-03-20 12:44:29.019 ThaliTest[1395:3260294] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:29.020 ThaliTest[1395:3260294] client session: no connect callback (server initiated)
,2016-03-20 12:44:33.450 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:44:33.462 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:37.665 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-20 12:44:40.671 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:40.672 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:44:40.672 ThaliTest[1395:3259594] client session: reverseConn,ect
2016-03-20 12:44:40.673 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:41.159 ThaliTest[1395:3260323] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:41.160 ThaliTest[1395:3260323] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:44:41.160 ThaliTest[1395:3260323] client session: disconnect
,2016-03-20 12:44:41.160 ThaliTest[1395:3260323] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:41.162 ThaliTest[1395:3260323] client session: no connect callback (server initiated)
,2016-03-20 12:44:50.673 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-20 12:44:53.450 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:44:53.463 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:53.689 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:53.689 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:44:53.690 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:44:53.690 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:44:54.461 ThaliTest[1395:3260361] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:54.461 ThaliTest[1395:3260361] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:44:54.4,62 ThaliTest[1395:3260361] client session: disconnect
2016-03-20 12:44:54.462 ThaliTest[1395:3260361] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:44:54.463 ThaliTest[1395:3260361] client session: no connect callback (server initiated)
,2016-03-20 12:45:03.691 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-20 12:45:06.704 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:06.705 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:45:06.706 ThaliTest[1395:3259594] client session: reverseConn,ect
2016-03-20 12:45:06.706 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:06.937 ThaliTest[1395:3260361] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:06.938 ThaliTest[1395:3260361] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:45:06.9,38 ThaliTest[1395:3260361] client session: disconnect
2016-03-20 12:45:06.938 ThaliTest[1395:3260361] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:06.940 ThaliTest[1395:3260361] client session: no connect callback (server initiated)
,2016-03-20 12:45:13.450 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:45:13.463 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:16.707 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-20 12:45:19.719 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:19.720 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:45:19.720 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:45:19.721 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:20.019 ThaliTest[1395:3260361] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:20.019 ThaliTest[1395:3260361] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:45:20.0,19 ThaliTest[1395:3260361] client session: disconnect
2016-03-20 12:45:20.019 ThaliTest[1395:3260361] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:20.021 ThaliTest[1395:3260361] client session: no connect callback (server initiated)
,2016-03-20 12:45:29.721 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-20 12:45:32.732 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:32.733 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:45:32.734 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:45:32.734 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:33.136 ThaliTest[1395:3260433] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:33.138 ThaliTest[1395:3260433] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:45:33.138 ThaliTest[1395:3260433] client session: disconnect
2016-03-20 12:45:33.138 ThaliTest[1395:3260433] client session:, stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:33.139 ThaliTest[1395:3260433] client session: no connect callback (server initiated)
,2016-03-20 12:45:33.450 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:45:33.464 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:42.735 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-20 12:45:42.911 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:45:42.912 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:45:42.914 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
,2016-03-20 12:45:42.914 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
,2016-03-20 12:45:42.915 ThaliTest[1395:3259594] multipeer manager: stop client timer
2016-03-20 12:45:42.915 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-20 12:45:44.142 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:45:44.143 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:9
2016-03-20 12:45:44.143 ThaliTest[1395:3259594] multipeer m,anager: start client restart timer: 0x156d0a80
2016-03-20 12:45:44.143 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:9
2016-03-20 12:45:44.144 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
2016-03-20 12:45:44.145 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-20 12:45:44.146 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
ok 161 Can call startListeningForAdvertisements without error
,2016-03-20 12:45:44.559 ThaliTest[1395:3259393] client: found new peer: F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:44.560 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:44.560 ThaliTest[1395:3,259594] client: server will connect
2016-03-20 12:45:44.561 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:45:44.561 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:45.118 ThaliTest[1395:3260436] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:45.119 ThaliTest[1395:3260436] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:45:45.119 ThaliTest[1395:3260436] client session: disconnect
2016-03-20 12:45:45.119 ThaliTest[1395:3260436] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:45.120 ThaliTest[1395:3260436] client session: no connect callback (server initiated)
,2016-03-20 12:45:45.370 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:45:45.370 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:45:49.826 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:45:49.827 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:45:49.827 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:45:52.936 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:45:52.936 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:45:52.936 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:45:54.562 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-20 12:45:56.113 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:45:56.114 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:45:56.114 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:45:57.567 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:57.568 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:45:57.568 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:45:57.569 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:57.689 ThaliTest[1395:3260361] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:45:57.689 ThaliTest[1395:3260361] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
2016-03-20 12:45:57.690 ThaliTest[1395:3260361] client session: disconnect
,2016-03-20 12:45:57.690 ThaliTest[1395:3260361] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:8
,2016-03-20 12:45:57.692 ThaliTest[1395:3260361] client session: no connect callback (server initiated)
,2016-03-20 12:45:59.258 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:45:59.258 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:45:59.258 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:46:02.731 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:46:02.731 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:46:02.731 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:46:04.145 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:46:04.157 ThaliTest[1395:3259393] client: found updated peer: F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:46:06.151 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:46:06.151 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:46:06.151 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:46:07.569 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-20 12:46:09.287 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:46:09.288 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:46:09.288 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:46:10.576 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:10.577 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:46:10.578 ThaliTest[1395:3259594] client session: reverseConn,ect
2016-03-20 12:46:10.578 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:46:10.637 ThaliTest[1395:3260361] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:9
2016-03-20 12:46:10.637 ThaliTest[1395:3260361] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
,2016-03-20 12:46:10.637 ThaliTest[1395:3260361] client session: disconnect
2016-03-20 12:46:10.639 ThaliTest[1395:3260361] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:46:10.640 ThaliTest[1395:3260361] client session: no connect callback (server initiated)
,2016-03-20 12:46:12.373 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:46:12.373 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:46:12.374 ThaliTest[1395:3259393], server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:46:15.506 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:46:15.506 ThaliTest[1395:3259393] server: disconnecting to refresh session (F82F884A-9394-418C-8996-A62FEDB8DD77)
2016-03-20 12:46:15.506 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:9 != 5A342616-0ECA-48AE-829A-448F633DC8C8:8)
,2016-03-20 12:46:20.579 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-20 12:46:23.583 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:23.584 ThaliTest[1395:3259594] client: server will connect
2016-03-20 12:46:23.585 ThaliTest[1395:3259594] client session: reverseConnect
2016-03-20 12:46:23.585 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:46:24.145 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:46:24.160 ThaliTest[1395:3259393] client: found existing peer: F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:46:33.586 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-20 12:46:36.591 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:36.592 ThaliTest[1395:3259594] client: already connect(ing/ed) to F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:36.592 Thali,Test[1395:3259594] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-20 12:46:39.613 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:39.614 ThaliTest[1395:3259594] client: already connect(ing/ed) to F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:39.615 ThaliTest[1395:3259594] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-20 12:46:42.629 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:42.629 ThaliTest[1395:3259594] client: already connect(ing/ed) to F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:42.630 Thali,Test[1395:3259594] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-20 12:46:44.145 ThaliTest[1395:3259393] multipeer manager: restart client
,2016-03-20 12:46:45.648 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:45.648 ThaliTest[1395:3259594] client: already connect(ing/ed) to F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:45.649 Thali,Test[1395:3259594] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-20 12:46:48.662 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:48.663 ThaliTest[1395:3259594] client: already connect(ing/ed) to F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:48.663 ThaliTest[1395:3259594] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-20 12:46:51.676 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:51.677 ThaliTest[1395:3259594] client: already connect(ing/ed) to F82F884A-9394-418C-8996-A62FEDB8DD77:8
2016-03-20 12:46:51.677 ThaliTest[1395:3259594] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-20 12:46:51.952 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-20 12:46:51.953 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-20 12:46:51.955 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
,2016-03-20 12:46:51.955 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
,2016-03-20 12:46:51.956 ThaliTest[1395:3259594] client session: disconnect
2016-03-20 12:46:51.957 ThaliTest[1395:3259594] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:9
2016-03-20 12:46:51.957 ThaliTest[1395:3259594] multipeer m,anager: stop client timer
2016-03-20 12:46:51.958 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-20 12:46:53.379 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:53.380 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:53.381 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:53.382 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-20 12:46:54.120 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-20 12:46:54.122 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-20 12:46:54.123 ThaliTest[1395:3259594] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:54.125 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-20 12:46:54.592 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:54.592 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:54.593 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:54.594 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65517
,2016-03-20 12:46:54.736 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:46:54.737 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-20 12:46:54.739 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:46:54.740 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-20 12:46:54.958 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:54.959 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:46:54.959 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:46:54.959 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:46:54.960 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-20 12:46:55.092 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:55.093 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:55.093 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:55.094 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65519
,2016-03-20 12:46:55.365 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
2016-03-20 12:46:55.365 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:46:55.366 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
ok 169 no errors
,2016-03-20 12:46:55.368 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:46:55.370 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
ok 170 still no errors
,# setup
,2016-03-20 12:46:55.523 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:55.523 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:46:55.524 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:46:55.524 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
2016-03-20 12:46:55.524 ThaliTest[1395:3259594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-20 12:46:55.525 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-20 12:46:55.682 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:55.683 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:55.683 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:55.685 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65521
,2016-03-20 12:46:55.826 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:46:55.827 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:10
,2016-03-20 12:46:55.828 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
,2016-03-20 12:46:55.831 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:10
,2016-03-20 12:46:55.837 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening: success
,ok 171 no errors
,2016-03-20 12:46:55.841 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
,2016-03-20 12:46:55.842 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
,2016-03-20 12:46:55.845 ThaliTest[1395:3259594] multipeer manager: stop client timer
,2016-03-20 12:46:55.848 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:11
,2016-03-20 12:46:55.856 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
,2016-03-20 12:46:55.858 ThaliTest[1395:3259594] THEMultipeerManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:11
,2016-03-20 12:46:55.861 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening: success
,ok 172 still no errors
,# setup
,2016-03-20 12:46:56.176 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:56.176 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:46:56.176 ThaliTest[1395:3259594] multipeer manager: stop client timer
2016-03-20 12:46:56.177 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
2016-03-20 12:46:56.177 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-20 12:46:56.180 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #stopAdvertisingAndListening many times
,2016-03-20 12:46:56.500 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:56.500 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:56.500 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:56.502 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65525
,2016-03-20 12:46:56.705 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:56.705 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:46:56.705 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 173 no errors
,2016-03-20 12:46:56.707 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:56.707 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:46:56.707 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: success
ok 174 still no errors
,# setup
,2016-03-20 12:46:56.893 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:46:56.894 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:46:56.894 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:46:56.894 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-20 12:46:56.895 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,# 45. can get the network status before starting
,2016-03-20 12:46:57.237 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:57.238 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:57.239 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:57.240 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 175 network status should have certain non-empty properties
,# setup
,# 46. error returned with bad router
,2016-03-20 12:46:58.700 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:58.701 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:58.702 ThaliTest[1395:3259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:58.703 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 176 specific error expected
,# setup
,# 47. can do HTTP requests between peers
,2016-03-20 12:46:59.329 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:46:59.329 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:46:59.330 ThaliTest[1395:3,259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:46:59.332 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65527
,2016-03-20 12:46:59.559 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements
2016-03-20 12:46:59.559 ThaliTest[1395:3259594] multipeer manager: start client restart timer: 0x156d0a80
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-20 12:46:59.560 ThaliTest[1395:3259594] jxcore: startListeningForAdvertisements: success
,2016-03-20 12:46:59.562 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening
2016-03-20 12:46:59.563 ThaliTest[1395:3259594] server: starting 5A342616-0ECA-48AE-829A-448F633DC8C8:12
2016-03-20 12:46:59.563 ThaliTest[1395:3259594] THEMultipe,erManager initialized peer 5A342616-0ECA-48AE-829A-448F633DC8C8:12
2016-03-20 12:46:59.563 ThaliTest[1395:3259594] jxcore: startUpdateAdvertisingAndListening: success
,2016-03-20 12:47:00.903 ThaliTest[1395:3259393] client: found new peer: F82F884A-9394-418C-8996-A62FEDB8DD77:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,ok 177 found a peer! {"peerIdentifier":"F82F884A-9394-418C-8996-A62FEDB8DD77:9","portNumber":65529,"hostAddress":"127.0.0.1"}
,DEBUG createPeerListener: first connection
,2016-03-20 12:47:00.930 ThaliTest[1395:3259594] jxcore: connect F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:47:00.930 ThaliTest[1395:3259594] client: server will connect
,2016-03-20 12:47:00.931 ThaliTest[1395:3259594] client session: reverseConnect
,2016-03-20 12:47:00.932 ThaliTest[1395:3259594] client session: stateChange:0->1 F82F884A-9394-418C-8996-A62FEDB8DD77:9
,2016-03-20 12:47:02.315 ThaliTest[1395:3259393] multipeer session: reset timer
2016-03-20 12:47:02.315 ThaliTest[1395:3259393] server: rejecting invitation from F82F884A-9394-418C-8996-A62FEDB8DD77 due to previous generation (5A342616-0ECA-48AE-829A-448F633DC8C8:12 != 5A342616-0ECA-48AE-829A-448F633DC8C8:9)
,2016-03-20 12:47:02.374 ThaliTest[1395:3260581] client session: not connected F82F884A-9394-418C-8996-A62FEDB8DD77:9
2016-03-20 12:47:02.374 ThaliTest[1395:3260581] client session: onLinkFailure: F82F884A-9394-418C-8996-A62FEDB8DD77
,2016-03-20 12:47:02.375 ThaliTest[1395:3260581] client session: disconnect
2016-03-20 12:47:02.376 ThaliTest[1395:3260581] client session: stateChange:1->0 F82F884A-9394-418C-8996-A62FEDB8DD77:9
2016-03-20 12:47:02.377 ThaliTest[1395:3260581] client session: no connect callback (server initiated)
,2016-03-20 12:47:10.932 ThaliTest[1395:3259393] jxcore: connect: fail: Timed out awaiting reverse connection
,WARN createPeerListener: 
,DEBUG createPeerListener: failedConnection
,DEBUG createPeerListener: failed incoming connection because of mux promise failueTimed out awaiting reverse connection
,not ok 178 Error: socket hang up -2
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-20 12:47:11.764 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening
2016-03-20 12:47:11.764 ThaliTest[1395:3259594] THEMultipeerManager stopping peer
2016-03-20 12:47:11.764 ThaliTest[1395:3259594] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-20 12:47:11.765 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements
2016-03-20 12:47:11.765 ThaliTest[1395:3259594] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-20 12:47:11.766 ThaliTest[1395:3259594] jxcore: stopListeningForAdvertisements: success
,# 48. Can do requests between peers after start and stop
,2016-03-20 12:47:11.940 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:47:11.941 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:47:11.941 ThaliTest[1395:3259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:47:11.943 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 179 (unnamed assert)
,# setup
,# 49. We successfully receive and replay discoveryAdvertisingStateUpdate
,2016-03-20 12:47:12.941 ThaliTest[1395:3259594] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-20 12:47:12.942 ThaliTest[1395:3259594] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-20 12:47:12.942 ThaliTest[1395:3259594] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-20 12:47:12.944 ThaliTest[1395:3259594] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 180 (unnamed assert)
,# setup
,# 50. Test BEACONS_RETRIEVED_AND_PARSED locally
,# teardown
,ok 181 peerIdentifier should be hello
,ok 182 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 183 good beacon
,ok 184 good preAmble
,ok 185 public keys match!
,ok 186 must return null after successful call
,# setup
,# 51. Test HTTP_BAD_RESPONSE locally
,# teardown
,ok 187 Response should be HTTP_BAD_RESPONSE
,ok 188 must return null after successful call
,# setup
,# 52. Test NETWORK_PROBLEM locally
,# teardown
,ok 189 Response should be NETWORK_PROBLEM
,ok 190 reject reason should be: Could not establish TCP connection
,# setup
,# 53. Test timeout locally
,# teardown
,ok 191 Should be NETWORK_PROBLEM caused by timeout
,ok 192 reject reason should be Could not establish TCP connection
,# setup
,# 54. Call the start two times
,# teardown
,ok 193 Call start once
,ok 194 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 195 must return null after successful call.
,# setup
,# 55. Call the kill before calling the start
,# teardown
,ok 196 Should be Killed
,ok 197 Start after killed
,# setup
,# 56. Call the kill immediately after the start
,# teardown
,ok 198 Should be KILLED
,ok 199 must return null after successful kill
,# setup
,# 57. Call the kill while waiting a response from the server
,# teardown
,ok 200 Should be KILLED
,ok 201 must return null after successful kill
,# setup
,# 58. Test to exceed the max content size locally
,# teardown
,ok 202 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 203 must return null after successful call
,# setup
,# 59. Close the server socket while the client is waiting a response from the server. Local test.
,# teardown
,ok 204 Should be NETWORK_PROBLEM caused closing server socket
,ok 205 Should be Could not establish TCP connection
,# setup
,# 60. Close the client socket while the client is waiting a response from the server. Local test.
,# teardown
,ok 206 Should be NETWORK_PROBLEM caused closing client socket
,ok 207 Should be Could not establish TCP connection
,# setup
,# 61. #generatePreambleAndBeacons bad args
,# teardown
,ok 208 publicKeysToNotify cannot be null
,ok 209 ecdh for local device cannot be null
,ok 210 milliseconds cannot be less than 0
,ok 211 milliseconds cannot be 0
,ok 212 milliseconds cannot be greater than one_day
,# setup
,# 62. #generatePreambleAndBeacons empty keys to notify
,# teardown
,ok 213 should be equal
,# setup
,# 63. #generatePreambleAndBeacons multiple keys to notify
,# teardown
,ok 214 should be equal
,ok 215 should be equal
,ok 216 (unnamed assert)
,ok 217 should be equal
,# setup
,# 64. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,# teardown
,ok 218 should throw
,# setup
,# 65. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,# teardown
,ok 219 Preamble expiration must be a 64 bit integer
,# setup
,# 66. #parseBeacons expiration out of range lower
,# teardown
,ok 220 Expiration out of range
,# setup
,# 67. #parseBeacons expiration out of range lower
,# teardown
,ok 221 Expiration out of range
,# setup
,# 68. #parseBeacons no beacons returns null
,# teardown
,ok 222 should be equal
,# setup
,# 69. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,# teardown
,ok 223 Malformed encrypted beacon key ID
,# setup
,# 70. #parseBeacons addressBookCallback fails decrypt
,# teardown
,ok 224 should be equal
,# setup
,# 71. #parseBeacons addressBookCallback returns no matches
,# teardown
,ok 225 should be equal
,ok 226 should be equal
,# setup
,# 72. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 227 should be equal
,ok 228 should be equal
,# setup
,# 73. #parseBeacons addressBookCallback returns public key
,# teardown
,ok 229 right number of calls to address book
,ok 230 good preAmble
,ok 231 good unencryptedKeyId
,ok 232 good beacon
,# setup
,# 74. validate generatePskIdentityField
,# teardown
,ok 233 decoded buffers match
,# setup
,# 75. validate generatePskSecret
,# teardown
,ok 234 secrets match
,# setup
,# 76. Start and stop ThaliNotificationServer
,# teardown
,ok 235 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 236 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# setup
,# 77. Pass an empty array to ThaliNotificationServer.start
,# teardown
,ok 237 StartUpdateAdvertisingAndListening should not be called
,ok 238 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 239 no error
,ok 240 should be 204
,# setup
,# 78. Pass a string to ThaliNotificationServer.start
,# teardown
,ok 241 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 79. Pass an empty parameter to ThaliNotificationServer.start
,# teardown
,ok 242 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 80. Make an HTTP request to /NotificationBeacons
,# teardown
,ok 243 no error
,ok 244 should be 200
,ok 245 should be equal
,ok 246 should be equal
,ok 247 (unnamed assert)
,ok 248 no error
,ok 249 should be 204
,# setup
,# 81. Make an HTTP request to /NotificationBeacons (no keys)
,# teardown
,ok 250 error should be null
,ok 251 should be 204
,# setup
,# 82. Make an HTTP request to /NotificationBeaconsbefore calling start
,# teardown
,ok 252 should be 404
,# setup
,# 83. #testThaliPeerAction - test getters
,# teardown
,ok 253 getPeerIdentifier
,ok 254 getConnectionType
,ok 255 getActionType
,ok 256 getActionState
,# setup
,# 84. #testThaliPeerAction - start and kill
,# teardown
,ok 257 initial state
,ok 258 after start
,ok 259 after kill
,# setup
,# 85. #testThaliPeerAction - double start
,# teardown
,ok 260 should be equal
,# setup
,# 86. #testThaliPeerAction - start after kill
,# teardown
,ok 261 clean kill
,ok 262 should be equal
,# setup
,# 87. #testThaliPeerAction - make sure ids are unique
,# teardown
,ok 263 should not be equal
,# setup
,# 88. Test PeerConnectionInformation basics
,# teardown
,ok 264 getHostAddress works
,ok 265 getPortNumber works
,ok 266 getSuggestedTCPTimeout works
,# setup
,# 89. Test PeerDictionary basic functionality
,# teardown
,ok 267 Entry counter must be 1
,ok 268 Size must be 1
,ok 269 Entry counter must be 2
,ok 270 Size must be 2
,ok 271 Entry2 should not be found
,ok 272 Size must be 1
,ok 273 Size must be 0
,ok 274 entry not found must be thrown
,# setup
,# 90. Test PeerDictionary with multiple entries.
,# teardown
,ok 275 Size must be100
,ok 276 Entries between 20 and MAXSIZE + 20 should exist
,ok 277 WAITING state entry should not be removed
,# setup
,# 91. RESOLVED entries are removed before WAITING state entry.
,# teardown
,ok 278 Entries between 6 and MAXSIZE + 4 should exist
,ok 279 Size should be MAXSIZE
,ok 280 Size should be MAXSIZE+6
,# setup
,# 92. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,# teardown
,ok 281 WAITING state entry should not be removed
,ok 282 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 283 Size should be MAXSIZE
,ok 284 entryCounter should be MAXSIZE+6
,# setup
,# 93. When CONTROLLED_BY_POOL entry is removed and kill is called.
,# teardown
,ok 285 Kill should be called once
,ok 286 Size should be 100
,# setup
,# 94. #ThaliPeerPoolInterface - bad enqueues
,# teardown
,ok 287 null arg
,ok 288 wrong arg type
,ok 289 wrong state
,# setup
,# 95. #ThaliPeerPoolInterface - do not allow same object type
,# teardown
,ok 290 good enqueue
,ok 291 should be equal
,# setup
,# 96. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,# teardown
,ok 292 good enqueue
,ok 293 2nd good enqueue
,ok 294 we are in the pool
,ok 295 We are out of the pool
ok 296 Action was killed
,ok 297 The original kill was called too
,ok 298 second item is still in queue
,# setup
,# 97. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,# teardown
,ok 299 good enqueue
ok 300 first kill
,ok 301 second NOOP kill
,# setup
,# 98. compareBufferArrays
,# teardown
,ok 302 should throw
,ok 303 should throw
,ok 304 (unnamed assert)
,ok 305 (unnamed assert)
,ok 306 (unnamed assert)
,ok 307 (unnamed assert)
,ok 308 (unnamed assert)
,# setup
,# 99. Call start twice and get error
,# teardown
,ok 309 should throw
,# setup
,# 100. Start and make sure it runs
,# teardown
,# setup
,# 101. Make sure getTimeWhenRun is right after start
,# teardown
,ok 310 (unnamed assert)
,# setup
,# 102. Make sure getTimeWhenRun is -1 after function is called
,# teardown
,ok 311 should be equal
,# setup
,# 103. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,# teardown
,ok 312 should be equal
,ok 313 should be equal
,ok 314 should throw
,# setup
,# 104. Test TransientState
,# teardown
,ok 315 should throw
,ok 316 should throw
,ok 317 should be equal
,ok 318 should be equal
,ok 319 should be equal
,ok 320 should be equal
,ok 321 (unnamed assert)
,ok 322 (unnamed assert)
,# setup
,# 105. No peers and empty database
,# teardown
,ok 323 verify failed
ok 324 constructor called once
,ok 325 constructor called with right args
,ok 326 match start arg
,ok 327 start called once
,ok 328 stop called once
,ok 329 stop after start
,# setup
,# 106. One peer and empty DB
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 330 verify failed
,ok 331 constructor called once
,ok 332 constructor called with right args
,ok 333 match start arg
,ok 334 start called once
,ok 335 stop called once
,ok 336 stop after start
,# setup
,# 107. One peer with _Local set behind current seq
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 337 verify failed
,ok 338 constructor called once
,ok 339 constructor called with right args
,ok 340 match start arg
,ok 341 start called once
,ok 342 stop called once
,ok 343 stop after start
,# setup
,# 108. One peer with _Local set equal to current seq
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 344 verify failed
,ok 345 constructor called once
,ok 346 constructor called with right args
,ok 347 match start arg
,ok 348 start called once
,ok 349 stop called once
,ok 350 stop after start
,# setup
,# 109. One peer with _Local set ahead of current seq (and no this should not happen)
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 351 verify failed
,ok 352 constructor called once
,ok 353 constructor called with right args
,ok 354 match start arg
,ok 355 start called once
,ok 356 stop called once
,ok 357 stop after start
,# setup
,# 110. Three peers, one not in DB, one behind and one ahead
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 358 verify failed
,ok 359 constructor called once
,ok 360 constructor called with right args
,ok 361 match start arg
,ok 362 start called once
,ok 363 stop called once
,ok 364 stop after start
,# setup
,# 111. More than maximum peers, make sure we only send maximum allowed
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 365 verify failed
,ok 366 constructor called once
,ok 367 constructor called with right args
,ok 368 match start arg
,ok 369 start called once
,ok 370 stop called once
,ok 371 stop after start
,# setup
,# 112. two peers with empty DB, update the doc
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 372 verify failed
,ok 373 constructor called once
,ok 374 constructor called with right args
,ok 375 last start before stop
,ok 376 empty first start
,ok 377 full second start
,ok 378 only 2 timers
,# setup
,# 113. add doc and make sure tokens refresh when they expire
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 379 verify failed
,ok 380 constructor called once
,ok 381 constructor called with right args
,ok 382 start before stop
,ok 383 We got at least 3 calls to start
,ok 384 at least 3
,ok 385 default 1
,ok 386 1 run
,ok 387 default 2
,ok 388 2 run
,ok 389 default 3
,# setup
,# 114. start and stop and start and stop
,# teardown
,ok 390 start out null
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 391 back to null
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 392 still null
,ok 393 verify failed
,ok 394 constructor called once
,ok 395 constructor called with right args
,ok 396 first start before first stop
,ok 397 first stop before second start
,ok 398 second start before second stop
,# setup
,# 115. two identical starts in a row
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 399 verify failed
,ok 400 constructor called once
,ok 401 constructor called with right args
,ok 402 (unnamed assert)
,# setup
,# 116. two different starts in a row
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 403 verify failed
,ok 404 constructor called once
,ok 405 constructor called with right args
,ok 406 (unnamed assert)
,ok 407 (unnamed assert)
,# setup
,# 117. two stops and a start and two stops
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 408 verify failed
,ok 409 constructor called once
,ok 410 constructor called with right args
,ok 411 start before stop
,# setup
,# 118. we properly enqueue requests so no then needed
,# teardown
,DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
,ok 412 verify failed
,ok 413 constructor called once
,ok 414 constructor called with right args
,ok 415 start before stop
,# setup
,# 119. test calculateSeqPointKeyId
,# teardown
,ok 416 should be equal
,ok 417 should be equal
,# setup
,# 120. can create servers manager
,# teardown
,ok 418 serversManager must not be null
,ok 419 serversManager must be an object
,# setup
,# 121. calling stop without start causes error
,# teardown
,ok 420 We need to call start first
,# setup
,# 122. can start/stop servers manager
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49180
,ok 421 port must be in range
,# setup
,# 123. starting twice resolves with listening port
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49181
,ok 422 second start should return same port
,# setup
,# 124. terminateIncomingConnection will terminate a connection
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49183
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 423 we should be connected
,DEBUG createNativeListener: incoming socket close
,ok 424 now we are disconnected
,# setup
,# 125. terminate an Outgoing connection will terminate the server
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49185
,# setup
,# 126. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49186
,# setup
,# 127. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,ok 425 should be in started state
,# teardown
,ok 426 peer identifier should match
,ok 427 host address should match
,ok 428 port should match
,ok 429 host address should be null
,ok 430 port should should be null
,# setup
,ok 431 should not be in started state
,# 128. #startUpdateAdvertisingAndListening should use different USN after every invocation
,ok 432 should be in started state
,# teardown
,ok 433 USN should have changed from the first one
,ok 434 when receiving the second byebye, the first USN should be already set
,# setup
,ok 435 should not be in started state
,# 129. messages with invalid location or USN should be ignored
,ok 436 should be in started state
,# teardown
,WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
,ok 437 should not have emitted with invalid port
,WARN thaliWifiInfrastructure: Received an invalid USN value: 
,ok 438 should not have emitted with invalid USN
,# setup
,ok 439 should not be in started state
,# 130. verify that Thali-specific messages are filtered correctly
,ok 440 should be in started state
,# teardown
,ok 441 irrelevant messages should be ignored
,ok 442 relevant messages should not be ignored
,ok 443 messages from this device should be ignored
,# setup
,ok 444 should not be in started state
,# 131. #startListeningForAdvertisements should fail if start not called
,ok 445 should be in started state
,# teardown
,ok 446 specific error should be returned
,# setup
,ok 447 should not be in started state
,# 132. #startUpdateAdvertisingAndListening should fail if start not called
,ok 448 should be in started state
,# teardown
,ok 449 specific error should be returned
,# setup
,ok 450 should not be in started state
,# 133. #start should fail if called twice in a row
,ok 451 should be in started state
,# teardown
,ok 452 specific error should be received
,# setup
,ok 453 should not be in started state
,# 134. should not be started after stop is called
,ok 454 should be in started state
,# teardown
,ok 455 should not be started
,ok 456 should not be listening
,ok 457 should not target listening
,ok 458 should not be advertising
,ok 459 should not target advertising
,# setup
,ok 460 should not be in started state
,# 135. #startUpdateAdvertisingAndListening should fail invalid router has been passed
,ok 461 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 462 specific error should be received
,# setup
,ok 463 should not be in started state
,# 136. #startUpdateAdvertisingAndListening should fail if router server starting fails
,ok 464 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
,ok 465 specific error expected
,# setup
,ok 466 should not be in started state
,# 137. #startUpdateAdvertisingAndListening should start hosting given router object
,ok 467 should be in started state
,# teardown
,ok 468 server should respond with code 200
,# setup
,ok 469 should not be in started state
,# 138. #stop can be called multiple times in a row
,ok 470 should be in started state
,# teardown
,ok 471 should be in stopped state
,ok 472 should still be in stopped state
,# setup
,ok 473 should not be in started state
,# 139. #startListeningForAdvertisements can be called multiple times in a row
,ok 474 should be in started state
,# teardown
,ok 475 should be in listening state
,ok 476 should still be in listening state
,# setup
,ok 477 should not be in started state
,# 140. #stopListeningForAdvertisements can be called multiple times in a row
,ok 478 should be in started state
,# teardown
,ok 479 should not be in listening state
,ok 480 should still not be in listening state
,# setup
,ok 481 should not be in started state
,# 141. #stopAdvertisingAndListening can be called multiple times in a row
,ok 482 should be in started state
,# teardown
,ok 483 should not be in advertising state
,ok 484 should still not be in advertising state
,# setup
,ok 485 should not be in started state
,# 142. functions are run from a queue in the right order
,ok 486 should be in started state
,# teardown
,ok 487 call order must match
,# setup
,ok 488 should not be in started state
,# 143. #ThaliPeerPoolDefault - single action
,# teardown
,ok 489 is an agent
,ok 490 enqueue is fine
,ok 491 Everything should be off the queue
,# setup
,# 144. #ThaliPeerPoolDefault - multiple actions
,# teardown
,ok 492 is an agent
,ok 493 first enqueue is fine
,ok 494 is an agent
,ok 495 second enqueue is fine
,ok 496 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 497 Queue is empty
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
