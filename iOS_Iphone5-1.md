#### Test 62548124d9c0fd9_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AE74BF83-2CA5-445C-A9F0-5B17AA49643A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/AE74BF83-2CA5-445C-A9F0-5B17AA49643A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124d9c0fd9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53089"
,(lldb)     command script import "/tmp/AE74BF83-2CA5-445C-A9F0-5B17AA49643A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-19 12:50:52.981 ThaliTest[1357:3108672] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2CB7B60B-5B64-45E8-AD43-E34742BB2B25/Library/Cookies/Cookies.binarycookies
,2016-03-19 12:50:53.093 ThaliTest[1357:3108672] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-19 12:50:53.095 ThaliTest[1357:3108672] Multi-tasking -> Device: YES, App: YES
,2016-03-19 12:50:53.116 ThaliTest[1357:3108672] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-19 12:50:55.274 ThaliTest[1357:3108672] Using UIWebView
,2016-03-19 12:50:55.279 ThaliTest[1357:3108672] [CDVTimer][handleopenurl] 0.422001ms
,2016-03-19 12:50:55.285 ThaliTest[1357:3108672] [CDVTimer][intentandnavigationfilter] 5.254984ms
2016-03-19 12:50:55.285 ThaliTest[1357:3108672] [CDVTimer][gesturehandler] 0.256956ms
2016-03-19 12:50:55.286 ThaliTest[1357:3108672] [CDVTimer][TotalPluginStartup] 6.990016ms
,2016-03-19 12:51:04.251 ThaliTest[1357:3108672] Resetting plugins due to page load.
,2016-03-19 12:51:08.053 ThaliTest[1357:3108672] Finished load of: file:///var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/index.html
,2016-03-19 12:51:08.254 ThaliTest[1357:3108672] JXcore Cordova plugin initializing
,2016-03-19 12:51:08.256 ThaliTest[1357:3108859] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-19 12:51:24.894 ThaliTest[1357:3108859] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-19 12:51:24.895 ThaliTest[1357:3108859] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-19 12:51:24.895 ThaliTest[1357:3108859] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-19 12:51:24.899 ThaliTest[1357:3108859] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/71DFF6BC-830D-443D-8516-4F8EE3EE920F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-19 12:51:38.517 ThaliTest[1357:3108672] THREAD WARNING: ['JXcore'] took '12920.684814' ms. Plugin should use a background thread.
,2016-03-19 12:51:38.518 ThaliTest[1357:3108800] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65106
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65108
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
,DEBUG createNativeListener: listening 65111
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
,DEBUG createNativeListener: listening 65115
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
,DEBUG createNativeListener: listening 65120
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
,DEBUG createNativeListener: listening 65124
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
,DEBUG createNativeListener: listening 65128
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
,DEBUG createNativeListener: listening 65132
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
,DEBUG createNativeListener: listening 65136
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
,DEBUG createNativeListener: listening 65188
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
,DEBUG createNativeListener: listening 65192
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
ok 65 fourth
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
,DEBUG createNativeListener: listening 65204
,2016-03-19 12:55:14.711 ThaliTest[1357:3108859] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 12:55:14.712 ThaliTest[1357:3108859] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-19 12:55:14.717 ThaliTest[1357:3108859] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-19 12:55:14.718 ThaliTest[1357:3108859] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-19 12:55:15.183 ThaliTest[1357:3108859] jxcore: stopAdvertisingAndListening
2016-03-19 12:55:15.183 ThaliTest[1357:3108859] THEMultipeerManager stopping peer
2016-03-19 12:55:15.184 ThaliTest[1357:3108859] jxcore: stopAdvertisingAndListening: success
2016-03-19 12:55:15.184 ThaliTest[1357:3108859] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-19 12:55:15.185 ThaliTest[1357,:3108859] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65206
,2016-03-19 12:55:15.897 ThaliTest[1357:3108859] jxcore: startListeningForAdvertisements
,2016-03-19 12:55:15.899 ThaliTest[1357:3108859] multipeer manager: start client restart timer: 0x16df5d30
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-19 12:55:15.902 ThaliTest[1357:3108859] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-19 12:55:15.956 ThaliTest[1357:3108859] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-19 12:55:15.958 ThaliTest[1357:3108859] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-19 12:55:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:55:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:56:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:56:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:56:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:57:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:57:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:57:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:58:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:58:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:58:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:59:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:59:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 12:59:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:00:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:00:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:00:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:01:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:01:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:01:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:02:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:02:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:02:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:03:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:03:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:03:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:04:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:04:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:04:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:05:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:05:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:05:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:06:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:06:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:06:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:07:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:07:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:07:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:08:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:08:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:08:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:09:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:09:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:09:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:10:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:10:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:10:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:11:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:11:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:11:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:12:15.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:12:35.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:12:55.901 ThaliTest[1357:3108672] multipeer manager: restart client
,2016-03-19 13:13:15.901 ThaliTest[1357:3108672] multipeer manager: restart client

```
