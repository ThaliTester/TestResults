#### Test 63998117be38304_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63998117be38304/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/95520A49-7834-43BB-B5B1-42B57EED7116/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/95520A49-7834-43BB-B5B1-42B57EED7116/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63998117be38304/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63998117be38304/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55462"
,(lldb)     command script import "/tmp/95520A49-7834-43BB-B5B1-42B57EED7116/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 08:45:04.473 ThaliTest[1588:3862384] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/69431745-278A-4BE7-83C9-DF9FB222A1EF/Library/Cookies/Cookies.binarycookies
,2016-03-24 08:45:04.596 ThaliTest[1588:3862384] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 08:45:04.599 ThaliTest[1588:3862384] Multi-tasking -> Device: YES, App: YES
,2016-03-24 08:45:04.622 ThaliTest[1588:3862384] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 08:45:06.816 ThaliTest[1588:3862384] Using UIWebView
,2016-03-24 08:45:06.821 ThaliTest[1588:3862384] [CDVTimer][handleopenurl] 0.506997ms
,2016-03-24 08:45:06.827 ThaliTest[1588:3862384] [CDVTimer][intentandnavigationfilter] 5.122960ms
2016-03-24 08:45:06.827 ThaliTest[1588:3862384] [CDVTimer][gesturehandler] 0.252008ms
2016-03-24 08:45:06.828 ThaliTest[1588:3862384] [CDVTimer][TotalPluginStartup] 7.251024ms
,2016-03-24 08:45:15.691 ThaliTest[1588:3862384] Resetting plugins due to page load.
,2016-03-24 08:45:19.970 ThaliTest[1588:3862384] Finished load of: file:///var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/index.html
,2016-03-24 08:45:20.181 ThaliTest[1588:3862384] JXcore Cordova plugin initializing
,2016-03-24 08:45:20.184 ThaliTest[1588:3862593] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 08:45:36.555 ThaliTest[1588:3862593] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 08:45:36.555 ThaliTest[1588:3862593] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 08:45:36.557 ThaliTest[1588:3862593] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 08:45:36.559 ThaliTest[1588:3862593] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A38E64-A459-4CD1-90E4-04FAB07686C4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 08:45:49.874 ThaliTest[1588:3862384] THREAD WARNING: ['JXcore'] took '12606.509033' ms. Plugin should use a background thread.
,2016-03-24 08:45:49.875 ThaliTest[1588:3862524] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51660
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51662
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
,DEBUG createNativeListener: listening 51665
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
,DEBUG createNativeListener: listening 51669
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
,DEBUG createNativeListener: listening 51674
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
,DEBUG createNativeListener: listening 51678
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
,DEBUG createNativeListener: listening 51682
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
,DEBUG createNativeListener: listening 51686
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
,DEBUG createNativeListener: listening 51690
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
,DEBUG createNativeListener: listening 51742
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
,DEBUG createNativeListener: listening 51746
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
,DEBUG createNativeListener: listening 51758
,2016-03-24 08:47:56.549 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 08:47:56.551 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-24 08:47:56.555 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 08:47:56.557 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-24 08:47:56.735 ThaliTest[1588:3862593] jxcore: stopAdvertisingAndListening
2016-03-24 08:47:56.735 ThaliTest[1588:3862593] THEMultipeerManager stopping peer
2016-03-24 08:47:56.735 ThaliTest[1588:3862593] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 08:47:56.736 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 08:47:56.737 ThaliTest[1588,:3862593] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51760
,2016-03-24 08:47:57.007 ThaliTest[1588:3862593] jxcore: startListeningForAdvertisements
,2016-03-24 08:47:57.009 ThaliTest[1588:3862593] multipeer manager: start client restart timer: 0x17ee9ef0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 08:47:57.011 ThaliTest[1588:3862593] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-24 08:47:57.033 ThaliTest[1588:3862593] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 08:47:57.036 ThaliTest[1588:3862593] jxcore: startListeningForAdvertisements: success
,ok 96 error should be null
,ok 97 error should be null
,# teardown
,2016-03-24 08:47:57.332 ThaliTest[1588:3862593] jxcore: stopAdvertisingAndListening
2016-03-24 08:47:57.333 ThaliTest[1588:3862593] THEMultipeerManager stopping peer
2016-03-24 08:47:57.333 ThaliTest[1588:3862593] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 08:47:57.333 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements
2016-03-24 08:47:57.333 ThaliTest[1588:3862593] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 08:47:57.335 ThaliTest[1588:3862593] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 51762
,2016-03-24 08:47:59.059 ThaliTest[1588:3862593] jxcore: startUpdateAdvertisingAndListening
2016-03-24 08:47:59.060 ThaliTest[1588:3862593] server: starting BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:1
2016-03-24 08:47:59.061 ThaliTest[1588:3862593] multipeer manager: start client restart timer: 0x17ee9ef0
,2016-03-24 08:47:59.061 ThaliTest[1588:3862593] THEMultipeerManager initialized peer BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:1
2016-03-24 08:47:59.065 ThaliTest[1588:3862593] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-24 08:47:59.129 ThaliTest[1588:3862593] jxcore: startUpdateAdvertisingAndListening
2016-03-24 08:47:59.130 ThaliTest[1588:3862593] THEMultipeerManager stopping peer
2016-03-24 08:47:59.130 ThaliTest[1588:3862593] multipeer manager: stop client ti,mer
2016-03-24 08:47:59.130 ThaliTest[1588:3862593] server: starting BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
2016-03-24 08:47:59.131 ThaliTest[1588:3862593] multipeer manager: start client restart timer: 0x17ee9ef0
2016-03-24 08:47:59.131 ThaliTest[1588:,3862593] THEMultipeerManager initialized peer BBAA638B-CF1B-44CE-A2B7-657CEC924ECB:2
2016-03-24 08:47:59.131 ThaliTest[1588:3862593] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-24 08:48:01.187 ThaliTest[1588:3862384] client: found new peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:48:03.389 ThaliTest[1588:3862384] client: found new peer: 00085AB7-1FE7-49C7-9134-44FA4AE132E8:2
,2016-03-24 08:48:05.442 ThaliTest[1588:3862384] client: lost peer: 00085AB7-1FE7-49C7-9134-44FA4AE132E8
2016-03-24 08:48:05.443 ThaliTest[1588:3862384] client session: onPeerLost: 00085AB7-1FE7-49C7-9134-44FA4AE132E8
,2016-03-24 08:48:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:48:19.145 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,appEnteredForeground wasn't registered
,2016-03-24 08:48:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:48:39.150 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:48:41.870 ThaliTest[1588:3862384] client: lost peer: EBA29E46-2D28-43EB-B896-31A127721C1F
2016-03-24 08:48:41.870 ThaliTest[1588:3862384] client session: onPeerLost: EBA29E46-2D28-43EB-B896-31A127721C1F
,2016-03-24 08:48:44.279 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:48:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:48:59.143 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:49:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:49:19.149 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,Disconnected from the test server
,2016-03-24 08:49:34.206 ThaliTest[1588:3862384] client: lost peer: EBA29E46-2D28-43EB-B896-31A127721C1F
2016-03-24 08:49:34.206 ThaliTest[1588:3862384] client session: onPeerLost: EBA29E46-2D28-43EB-B896-31A127721C1F
,2016-03-24 08:49:36.052 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:49:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:49:39.151 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:49:51.131 ThaliTest[1588:3862384] client: lost peer: EBA29E46-2D28-43EB-B896-31A127721C1F
2016-03-24 08:49:51.132 ThaliTest[1588:3862384] client session: onPeerLost: EBA29E46-2D28-43EB-B896-31A127721C1F
,2016-03-24 08:49:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:49:59.154 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:50:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:50:19.150 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:50:32.787 ThaliTest[1588:3862384] client: lost peer: EBA29E46-2D28-43EB-B896-31A127721C1F
2016-03-24 08:50:32.787 ThaliTest[1588:3862384] client session: onPeerLost: EBA29E46-2D28-43EB-B896-31A127721C1F
,2016-03-24 08:50:39.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:50:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:51:08.111 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:51:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:51:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:51:39.147 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:51:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:51:59.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:52:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:52:19.143 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:52:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:52:39.445 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:52:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:52:59.143 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:53:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:53:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:53:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:53:39.154 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:53:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:53:59.154 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:54:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:54:19.149 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:54:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:54:39.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:54:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:54:59.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:55:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:55:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:55:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:55:39.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:55:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:55:59.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:56:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:56:19.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:56:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:56:39.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:56:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:56:59.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:57:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:57:19.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:57:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:57:39.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:57:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:57:59.144 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:58:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:58:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:58:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:58:39.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:58:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:58:59.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:59:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:59:19.150 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:59:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:59:39.157 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 08:59:59.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 08:59:59.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:00:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:00:19.143 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:00:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:00:39.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:00:59.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:00:59.138 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:01:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:01:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:01:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:01:39.146 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:01:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:01:59.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:02:19.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:02:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:02:39.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:02:39.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:02:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:02:59.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:03:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:03:19.144 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:03:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:03:39.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:03:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:03:59.142 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:04:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:04:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:04:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:04:39.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:04:59.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:04:59.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:05:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:05:19.141 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:05:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:05:39.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:05:59.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:05:59.140 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:06:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:06:19.148 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:06:39.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:06:39.154 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:06:59.131 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:06:59.148 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2
,2016-03-24 09:07:19.132 ThaliTest[1588:3862384] multipeer manager: restart client
,2016-03-24 09:07:19.149 ThaliTest[1588:3862384] client: found existing peer: EBA29E46-2D28-43EB-B896-31A127721C1F:2

```
