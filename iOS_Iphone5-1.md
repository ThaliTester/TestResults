#### Test 625481246a7d362_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DA70EDED-D8EB-4B16-AD8E-71045C625A3D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/DA70EDED-D8EB-4B16-AD8E-71045C625A3D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246a7d362/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54361"
,(lldb)     command script import "/tmp/DA70EDED-D8EB-4B16-AD8E-71045C625A3D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 15:47:58.999 ThaliTest[1460:3437188] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/46DE1C76-0BB1-4231-924A-EC9FD7DABA67/Library/Cookies/Cookies.binarycookies
,2016-03-21 15:47:59.122 ThaliTest[1460:3437188] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 15:47:59.124 ThaliTest[1460:3437188] Multi-tasking -> Device: YES, App: YES
,2016-03-21 15:47:59.144 ThaliTest[1460:3437188] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 15:48:01.414 ThaliTest[1460:3437188] Using UIWebView
,2016-03-21 15:48:01.419 ThaliTest[1460:3437188] [CDVTimer][handleopenurl] 0.295997ms
,2016-03-21 15:48:01.424 ThaliTest[1460:3437188] [CDVTimer][intentandnavigationfilter] 5.296052ms
2016-03-21 15:48:01.425 ThaliTest[1460:3437188] [CDVTimer][gesturehandler] 0.258029ms
2016-03-21 15:48:01.425 ThaliTest[1460:3437188] [CDVTimer][TotalPluginS,tartup] 6.918013ms
,2016-03-21 15:48:11.085 ThaliTest[1460:3437188] Resetting plugins due to page load.
,2016-03-21 15:48:14.833 ThaliTest[1460:3437188] Finished load of: file:///var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/index.html
,2016-03-21 15:48:15.035 ThaliTest[1460:3437188] JXcore Cordova plugin initializing
,2016-03-21 15:48:15.036 ThaliTest[1460:3437393] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 15:48:31.572 ThaliTest[1460:3437393] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 15:48:31.573 ThaliTest[1460:3437393] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 15:48:31.574 ThaliTest[1460:3,437393] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 15:48:31.578 ThaliTest[1460:3437393] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B5490DED-5B7E-4EA0-951A-24A4BBB80D28/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 15:48:45.067 ThaliTest[1460:3437188] THREAD WARNING: ['JXcore'] took '12790.921143' ms. Plugin should use a background thread.
,2016-03-21 15:48:45.068 ThaliTest[1460:3437326] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50284
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50286
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
,DEBUG createNativeListener: listening 50289
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
,DEBUG createNativeListener: listening 50293
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
,DEBUG createNativeListener: listening 50298
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
,DEBUG createNativeListener: listening 50302
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
,DEBUG createNativeListener: listening 50307
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
,DEBUG createNativeListener: listening 50311
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
,DEBUG createNativeListener: listening 50315
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
,DEBUG createNativeListener: listening 50367
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
,DEBUG createNativeListener: listening 50371
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
,DEBUG createNativeListener: listening 50383
,2016-03-21 15:51:15.278 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 15:51:15.279 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 15:51:15.283 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 15:51:15.285 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 15:51:15.414 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:15.415 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:15.415 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 15:51:15.415 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 15:51:15.417 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50385
,2016-03-21 15:51:15.728 ThaliTest[1460:3437393] jxcore: startListeningForAdvertisements
,2016-03-21 15:51:15.730 ThaliTest[1460:3437393] multipeer manager: start client restart timer: 0x16673710
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 15:51:15.732 ThaliTest[1460:3437393] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-21 15:51:15.786 ThaliTest[1460:3437393] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 15:51:15.787 ThaliTest[1460:3437393] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 15:51:16.010 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:16.010 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:16.010 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 15:51:16.011 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
2016-03-21 15:51:16.011 ThaliTest[1460:3437393] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 15:51:16.012 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50387
,2016-03-21 15:51:16.656 ThaliTest[1460:3437393] jxcore: startUpdateAdvertisingAndListening
2016-03-21 15:51:16.656 ThaliTest[1460:3437393] server: starting C0BA8608-719D-463A-8E72-4FE4899E8EEF:1
2016-03-21 15:51:16.657 ThaliTest[1460:3437393] multipeer m,anager: start client restart timer: 0x16673710
2016-03-21 15:51:16.658 ThaliTest[1460:3437393] THEMultipeerManager initialized peer C0BA8608-719D-463A-8E72-4FE4899E8EEF:1
2016-03-21 15:51:16.658 ThaliTest[1460:3437393] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-21 15:51:16.682 ThaliTest[1460:3437393] jxcore: startUpdateAdvertisingAndListening
2016-03-21 15:51:16.682 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:16.683 ThaliTest[1460:3437393] multipeer manager: stop client ti,mer
2016-03-21 15:51:16.683 ThaliTest[1460:3437393] server: starting C0BA8608-719D-463A-8E72-4FE4899E8EEF:2
,2016-03-21 15:51:16.684 ThaliTest[1460:3437393] multipeer manager: start client restart timer: 0x16673710
2016-03-21 15:51:16.685 ThaliTest[1460:3437393] THEMultipeerManager initialized peer C0BA8608-719D-463A-8E72-4FE4899E8EEF:2
,2016-03-21 15:51:16.685 ThaliTest[1460:3437393] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-21 15:51:17.643 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:17.643 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:17.643 ThaliTest[1460:3437393] multipeer manager: stop client timer
20,16-03-21 15:51:17.643 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: success
2016-03-21 15:51:17.644 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 15:51:17.645 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50392
,2016-03-21 15:51:18.309 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:18.310 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:18.310 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-21 15:51:18.314 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:18.314 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:18.314 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-21 15:51:19.735 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:19.735 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:19.735 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 15:51:19.735 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 15:51:19.736 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50394
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 15:51:20.408 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening
2016-03-21 15:51:20.408 ThaliTest[1460:3437393] THEMultipeerManager stopping peer
2016-03-21 15:51:20.409 ThaliTest[1460:3437393] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 15:51:20.409 ThaliTest[1460:3437393] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 15:51:20.410 ThaliTest[1460,:3437393] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50396
,2016-03-21 15:51:20.884 ThaliTest[1460:3437393] jxcore: startListeningForAdvertisements
2016-03-21 15:51:20.884 ThaliTest[1460:3437393] multipeer manager: start client restart timer: 0x16673710
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 15:51:20.886 ThaliTest[1460:3437393] jxcore: startListeningForAdvertisements: success
,2016-03-21 15:51:20.907 ThaliTest[1460:3437393] jxcore: startUpdateAdvertisingAndListening
2016-03-21 15:51:20.908 ThaliTest[1460:3437393] server: starting C0BA8608-719D-463A-8E72-4FE4899E8EEF:3
2016-03-21 15:51:20.908 ThaliTest[1460:3437393] THEMultipeerManager initialized peer C0BA8608-719D-463A-8E72-4FE4899E8EEF:3
2016-03-21 15:51:20.909 ThaliTest[1460:3437393] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-21 15:51:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:52:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:52:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:52:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:53:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:53:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:53:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:54:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:54:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:54:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:55:00.885 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:55:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:55:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:56:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:56:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:56:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:57:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:57:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:57:40.885 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:58:00.885 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:58:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:58:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:59:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:59:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 15:59:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:00:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:00:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:00:40.885 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:01:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:01:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:01:40.885 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:02:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:02:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:02:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:03:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:03:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:03:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:04:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:04:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:04:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:05:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:05:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:05:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:06:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:06:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:06:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:07:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:07:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:07:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:08:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:08:20.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:08:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:09:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:09:20.885 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:09:40.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:10:00.886 ThaliTest[1460:3437188] multipeer manager: restart client
,2016-03-21 16:10:20.885 ThaliTest[1460:3437188] multipeer manager: restart client

```
