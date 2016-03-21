#### Test 625481246894564_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D5B21475-5105-47F3-90D2-7B70E78A0569/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D5B21475-5105-47F3-90D2-7B70E78A0569/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54163"
,(lldb)     command script import "/tmp/D5B21475-5105-47F3-90D2-7B70E78A0569/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 13:01:38.637 ThaliTest[1444:3417702] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4481AF96-BBA4-4C24-9973-51948904F2A4/Library/Cookies/Cookies.binarycookies
,2016-03-21 13:01:38.748 ThaliTest[1444:3417702] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 13:01:38.750 ThaliTest[1444:3417702] Multi-tasking -> Device: YES, App: YES
,2016-03-21 13:01:38.770 ThaliTest[1444:3417702] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 13:01:41.060 ThaliTest[1444:3417702] Using UIWebView
,2016-03-21 13:01:41.064 ThaliTest[1444:3417702] [CDVTimer][handleopenurl] 0.289977ms
,2016-03-21 13:01:41.070 ThaliTest[1444:3417702] [CDVTimer][intentandnavigationfilter] 5.703032ms
2016-03-21 13:01:41.071 ThaliTest[1444:3417702] [CDVTimer][gesturehandler] 0.253022ms
2016-03-21 13:01:41.071 ThaliTest[1444:3417702] [CDVTimer][TotalPluginS,tartup] 7.299006ms
,2016-03-21 13:01:50.156 ThaliTest[1444:3417702] Resetting plugins due to page load.
,2016-03-21 13:01:54.645 ThaliTest[1444:3417702] Finished load of: file:///var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/index.html
,2016-03-21 13:01:54.848 ThaliTest[1444:3417702] JXcore Cordova plugin initializing
,2016-03-21 13:01:54.850 ThaliTest[1444:3417879] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 13:02:11.475 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:02:11.475 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:02:11.476 ThaliTest[1444:3,417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-21 13:02:11.478 ThaliTest[1444:3417879] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F8351A34-0B89-4D77-99D0-64BE481A1DF2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 13:02:24.966 ThaliTest[1444:3417702] THREAD WARNING: ['JXcore'] took '12786.210205' ms. Plugin should use a background thread.
,2016-03-21 13:02:24.967 ThaliTest[1444:3417827] void SendDelegateMessage(NSInvocation *): delegate (webView:decidePolicyForNavigationAction:request:frame:decisionListener:) failed to return after waiting 10 seconds. main run loop mode: kCFRunLoopDefaultMode
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49771
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49773
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
,DEBUG createNativeListener: listening 49776
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
,DEBUG createNativeListener: listening 49781
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
,DEBUG createNativeListener: listening 49786
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
,DEBUG createNativeListener: listening 49791
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
,DEBUG createNativeListener: listening 49795
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
,DEBUG createNativeListener: listening 49799
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
ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,DEBUG createNativeListener: incoming socket close
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49803
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
,DEBUG createNativeListener: listening 49855
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
,DEBUG createNativeListener: listening 49859
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
ok 78 error should be null
,# 22. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 79 specific error should be returned
,# setup
,ok 80 error should be null
ok 81 error should be null
,# 23. should be able to call #stopListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49871
,2016-03-21 13:04:33.467 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:33.469 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 13:04:33.473 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:33.475 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 13:04:33.598 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:33.598 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:33.599 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:04:33.599 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:33.600 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49873
,2016-03-21 13:04:33.873 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
,2016-03-21 13:04:33.875 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:33.877 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
ok 89 error should be null
,2016-03-21 13:04:33.896 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:33.900 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 13:04:34.206 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:34.206 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:34.206 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:04:34.207 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
2016-03-21 13:04:34.207 ThaliTest[1444:3417879] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:34.208 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49875
,2016-03-21 13:04:34.787 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:34.788 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:1
2016-03-21 13:04:34.789 ThaliTest[1444:3417879] multipeer m,anager: start client restart timer: 0x16efbd50
2016-03-21 13:04:34.789 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:1
2016-03-21 13:04:34.789 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-21 13:04:34.828 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:34.829 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:34.829 ThaliTest[1444:3417879] multipeer manager: stop client ti,mer
2016-03-21 13:04:34.829 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:2
2016-03-21 13:04:34.830 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
2016-03-21 13:04:34.830 ThaliTest[1444:,3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:2
2016-03-21 13:04:34.830 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
,ok 97 error should be null
,# setup
,2016-03-21 13:04:35.274 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.274 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:35.274 ThaliTest[1444:3417879] multipeer manager: stop client timer
20,16-03-21 13:04:35.275 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
2016-03-21 13:04:35.275 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:35.276 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49880
,2016-03-21 13:04:35.729 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.729 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:35.729 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-21 13:04:35.733 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.734 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:35.734 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-21 13:04:35.859 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:35.859 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:35.860 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:04:35.860 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:35.861 ThaliTest[1444,:3417879] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49882
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 13:04:36.475 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:36.475 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:36.475 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
2016-03-21 13:04:36.476 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:36.477 ThaliTest[1444,:3417879] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49884
,2016-03-21 13:04:37.231 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
2016-03-21 13:04:37.232 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 13:04:37.233 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,2016-03-21 13:04:37.271 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:37.272 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:3
2016-03-21 13:04:37.272 ThaliTest[1444:3417879] THEMultipee,rManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:3
2016-03-21 13:04:37.272 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
ok 112 discovery state matches
ok 113 advertising state matches
,# setup
,2016-03-21 13:04:37.424 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:37.424 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:37.425 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:04:37.425 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
2016-03-21 13:04:37.425 ThaliTest[1444:3417879] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:37.426 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
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
,2016-03-21 13:04:42.408 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
2016-03-21 13:04:42.409 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 13:04:42.410 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
2016-03-21 13:04:42.412 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
,2016-03-21 13:04:42.413 ThaliTest[1444:3417879] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:42.414 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 13:04:42.710 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:04:42.711 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:42.713 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:42.713 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:42.714 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 13:04:43.200 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
2016-03-21 13:04:43.201 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 13:04:43.202 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-21 13:04:43.204 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:04:43.205 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 13:04:43.294 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
2016-03-21 13:04:43.295 ThaliTest[1444:3417879] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:43.296 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:43.298 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
,2016-03-21 13:04:43.298 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:43.300 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
# 34. Ca,n call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 13:04:46.307 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:46.307 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:4
2016-03-21 13:04:46.308 ThaliTest[1444:3417879] multipeer m,anager: start client restart timer: 0x16efbd50
2016-03-21 13:04:46.308 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:4
2016-03-21 13:04:46.308 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-21 13:04:46.310 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:46.310 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016,-03-21 13:04:46.310 ThaliTest[1444:3417879] multipeer manager: stop client timer
2016-03-21 13:04:46.310 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-21 13:04:46.401 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:04:46.403 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:46.404 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:46.405 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:46.405 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 13:04:46.666 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:46.666 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:5
2016-03-21 13:04:46.667 ThaliTest[1444:3417879] multipeer m,anager: start client restart timer: 0x16efbd50
2016-03-21 13:04:46.667 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:5
2016-03-21 13:04:46.667 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-21 13:04:46.668 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:46.669 ThaliTest[1444:3417879] THEMultipeerManager stopping pee,r
2016-03-21 13:04:46.669 ThaliTest[1444:3417879] multipeer manager: stop client timer
2016-03-21 13:04:46.669 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:6
2016-03-21 13:04:46.670 ThaliTest[1444:3417879] multipeer mana,ger: start client restart timer: 0x16efbd50
2016-03-21 13:04:46.674 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:6
2016-03-21 13:04:46.674 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-21 13:04:47.091 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-21 13:04:47.093 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:47.094 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
,2016-03-21 13:04:47.094 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
,2016-03-21 13:04:47.095 ThaliTest[1444:3417879] multipeer manager: stop client timer
,2016-03-21 13:04:47.096 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 13:04:48.773 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:48.774 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:04:48.774 ThaliTest[1444:3417879] multipeer m,anager: start client restart timer: 0x16efbd50
2016-03-21 13:04:48.775 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:7
2016-03-21 13:04:48.775 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-21 13:04:48.776 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 13:04:48.778 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 13:04:51.456 ThaliTest[1444:3417702] client: found new peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
ok 150 peerIdentifier must be a string
ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 13:04:53.284 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-21 13:04:53.285 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:04:53.286 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:04:53.287 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:04:53.287 ThaliTest[1444:3417879] multipeer manager: stop client timer
20,16-03-21 13:04:53.287 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 13:04:56.151 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:04:56.151 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:04:56.151 ThaliTest[1444:3417879] multipeer m,anager: start client restart timer: 0x16efbd50
2016-03-21 13:04:56.151 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:8
2016-03-21 13:04:56.152 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-21 13:04:56.153 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-21 13:04:56.154 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 13:04:58.178 ThaliTest[1444:3417702] client: found new peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"FE8F9526-AD74-40E1-9080-FD7FA9CC9,893:7","pleaseConnect":0}]
,2016-03-21 13:04:58.181 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:04:58.181 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:04:58.182 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:04:58.182 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
,2016-03-21 13:04:58.645 ThaliTest[1444:3418236] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:04:58.646 ThaliTest[1444:3418236] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:04:58.646 ThaliTest[1444:3418236] client session: disconnect
,2016-03-21 13:04:58.646 ThaliTest[1444:3418236] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
,2016-03-21 13:04:58.648 ThaliTest[1444:3418236] client session: no connect callback (server initiated)
,2016-03-21 13:04:59.309 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:04:59.309 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:02.992 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:02.993 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:02.993 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:07.190 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:07.190 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:07.190 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:08.183 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 13:05:10.855 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:10.855 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:10.856 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:11.188 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:05:11.189 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:05:11.189 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:05:11.190 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
,2016-03-21 13:05:11.296 ThaliTest[1444:3418236] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:05:11.297 ThaliTest[1444:3418236] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:05:11.2,97 ThaliTest[1444:3418236] client session: disconnect
,2016-03-21 13:05:11.297 ThaliTest[1444:3418236] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:05:11.299 ThaliTest[1444:3418236] client session: no connect callback (server initiated)
,2016-03-21 13:05:14.041 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:14.042 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:14.042 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:16.152 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:05:17.128 ThaliTest[1444:3417702] client: found updated peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8","pleaseConnect":0}]
,2016-03-21 13:05:17.187 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:17.187 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:17.187 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:20.285 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:20.285 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:20.286 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:21.190 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 13:05:23.466 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:23.466 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:23.466 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:24.206 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:05:24.207 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:05:24.208 ThaliTest[1444:3417879] client session: reverseConn,ect
2016-03-21 13:05:24.208 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:05:24.436 ThaliTest[1444:3418261] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:05:24.437 ThaliTest[1444:3418261] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:05:24.4,37 ThaliTest[1444:3418261] client session: disconnect
2016-03-21 13:05:24.437 ThaliTest[1444:3418261] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:05:24.439 ThaliTest[1444:3418261] client session: no connect callback (server initiated)
,2016-03-21 13:05:26.623 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:26.624 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:26.624 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:29.740 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:05:29.740 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:05:29.741 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:8 != ACF08CBB-018B-4F78-A189-81A63854F007:7)
,2016-03-21 13:05:34.209 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 13:05:36.153 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:05:36.166 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:05:37.215 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:05:37.216 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:05:37.216 ThaliTest[1444:3417879] client session: reverseConn,ect
2016-03-21 13:05:37.217 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:05:37.643 ThaliTest[1444:3418236] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:05:37.643 ThaliTest[1444:3418236] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:05:37.644 ThaliTest[1444:3418236] client session: disconnect
2016-03-21 13:05:37.644 ThaliTest[1444:3418236] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:05:37.646 ThaliTest[1444:3418236] client session: no connect callback (server initiated)
,2016-03-21 13:05:47.217 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 13:05:50.223 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:05:50.224 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:05:50.225 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:05:50.225 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:05:50.838 ThaliTest[1444:3418439] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:05:50.838 ThaliTest[1444:3418439] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
,2016-03-21 13:05:50.838 ThaliTest[1444:3418439] client session: disconnect
2016-03-21 13:05:50.839 ThaliTest[1444:3418439] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:05:50.840 ThaliTest[1444:3418439] client session: no connect callback (server initiated)
,2016-03-21 13:05:56.153 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:05:56.169 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:00.227 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 13:06:03.231 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:06:03.232 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:06:03.233 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:06:03.233 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:03.375 ThaliTest[1444:3418491] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:03.375 ThaliTest[1444:3418491] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:06:03.3,75 ThaliTest[1444:3418491] client session: disconnect
2016-03-21 13:06:03.375 ThaliTest[1444:3418491] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:03.377 ThaliTest[1444:3418491] client session: no connect callback (server initiated)
,2016-03-21 13:06:13.234 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 13:06:16.152 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:06:16.165 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:16.247 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:06:16.247 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:06:16.248 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:06:16.248 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:16.494 ThaliTest[1444:3418582] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:16.494 ThaliTest[1444:3418582] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
,2016-03-21 13:06:16.495 ThaliTest[1444:3418582] client session: disconnect
,2016-03-21 13:06:16.496 ThaliTest[1444:3418582] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:16.496 ThaliTest[1444:3418582] client session: no connect callback (server initiated)
,2016-03-21 13:06:26.249 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 13:06:29.264 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:06:29.265 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:06:29.265 ThaliTest[1444:3417879] client session: reverseConn,ect
2016-03-21 13:06:29.266 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:30.951 ThaliTest[1444:3418623] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:30.952 ThaliTest[1444:3418623] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:06:30.952 ThaliTest[1444:3418623] client session: disconnect
2016-03-21 13:06:30.953 ThaliTest[1444:3418623] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:30.953 ThaliTest[1444:3418623] client session: no connect callback (server initiated)
,2016-03-21 13:06:36.153 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:06:36.167 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:39.266 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 13:06:42.282 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:06:42.283 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:06:42.283 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:06:42.283 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:42.759 ThaliTest[1444:3418623] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:42.759 ThaliTest[1444:3418623] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:06:42.7,59 ThaliTest[1444:3418623] client session: disconnect
2016-03-21 13:06:42.760 ThaliTest[1444:3418623] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:42.760 ThaliTest[1444:3418623] client session: no connect callback (server initiated)
,2016-03-21 13:06:52.284 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 13:06:55.294 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:7
2016-03-21 13:06:55.295 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:06:55.295 ThaliTest[1444:3417879] client session: reverseConn,ect
2016-03-21 13:06:55.296 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:55.805 ThaliTest[1444:3418669] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:06:55.805 ThaliTest[1444:3418669] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
,2016-03-21 13:06:55.805 ThaliTest[1444:3418669] client session: disconnect
2016-03-21 13:06:55.806 ThaliTest[1444:3418669] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:06:55.807 ThaliTest[1444:3418669] client session: no connect callback (server initiated)
,2016-03-21 13:06:56.153 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:06:56.167 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:07:05.296 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 13:07:05.363 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 13:07:05.364 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:07:05.366 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
,2016-03-21 13:07:05.366 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
,2016-03-21 13:07:05.367 ThaliTest[1444:3417879] multipeer manager: stop client timer
,2016-03-21 13:07:05.367 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 159 Should be able to call stopAdvertisingAndListening in teardown
# 38. Can shift large amounts of data
,# teardown
,2016-03-21 13:07:06.054 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:07:06.054 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:06.055 ThaliTest[1444:3417879] multipeer m,anager: start client restart timer: 0x16efbd50
2016-03-21 13:07:06.055 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:9
2016-03-21 13:07:06.055 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 13:07:06.057 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-21 13:07:06.059 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 161 Can call startListeningForAdvertisements without error
,2016-03-21 13:07:06.845 ThaliTest[1444:3417702] client: found new peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:06.847 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:06.847 ThaliTest[1444:3,417879] client: server will connect
2016-03-21 13:07:06.847 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:07:06.847 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:07:07.332 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:07.332 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:08.309 ThaliTest[1444:3418623] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:08.309 ThaliTest[1444:3418623] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:07:08.309 ThaliTest[1444:3418623] client session: disconnect
,2016-03-21 13:07:08.309 ThaliTest[1444:3418623] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:07:08.312 ThaliTest[1444:3418623] client session: no connect callback (server initiated)
,2016-03-21 13:07:10.472 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:10.473 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:10.473 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:13.569 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:13.570 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:13.570 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:16.762 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:16.762 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:16.762 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:16.848 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 13:07:19.865 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:19.866 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:07:19.867 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:07:19.867 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:07:20.042 ThaliTest[1444:3418676] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:07:20.045 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:20.044 ThaliTest[1444:3418676] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
,2016-03-21 13:07:20.045 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
,2016-03-21 13:07:20.045 ThaliTest[1444:3418676] client session: disconnect
,2016-03-21 13:07:20.045 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:20.046 ThaliTest[1444:3418676] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
,2016-03-21 13:07:20.048 ThaliTest[1444:3418676] client session: no connect callback (server initiated)
,2016-03-21 13:07:23.979 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:23.980 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:23.980 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:26.056 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:07:26.069 ThaliTest[1444:3417702] client: found updated peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:07:27.243 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:27.244 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:27.244 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:29.868 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 13:07:30.791 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:30.791 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:30.792 ThaliTest[1444:3417702] server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:32.884 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:32.885 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:07:32.885 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:07:32.886 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:07:33.020 ThaliTest[1444:3418669] client session: not connected FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
2016-03-21 13:07:33.021 ThaliTest[1444:3418669] client session: onLinkFailure: FE8F9526-AD74-40E1-9080-FD7FA9CC9893
2016-03-21 13:07:33.0,21 ThaliTest[1444:3418669] client session: disconnect
,2016-03-21 13:07:33.021 ThaliTest[1444:3418669] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
2016-03-21 13:07:33.023 ThaliTest[1444:3418669] client session: no connect callback (server initiated)
,2016-03-21 13:07:33.888 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:33.888 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:33.888 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:37.100 ThaliTest[1444:3417702] multipeer session: reset timer
2016-03-21 13:07:37.100 ThaliTest[1444:3417702] server: disconnecting to refresh session (FE8F9526-AD74-40E1-9080-FD7FA9CC9893)
2016-03-21 13:07:37.101 ThaliTest[1444:3417702], server: rejecting invitation from FE8F9526-AD74-40E1-9080-FD7FA9CC9893 due to previous generation (ACF08CBB-018B-4F78-A189-81A63854F007:9 != ACF08CBB-018B-4F78-A189-81A63854F007:8)
,2016-03-21 13:07:42.887 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 13:07:45.892 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:45.893 ThaliTest[1444:3417879] client: server will connect
2016-03-21 13:07:45.894 ThaliTest[1444:3417879] client session: reverseConnect
2016-03-21 13:07:45.894 ThaliTest[1444:3417879] client session: stateChange:0->1 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:07:46.056 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:07:46.070 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:07:55.895 ThaliTest[1444:3417702] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 13:07:58.899 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:58.900 ThaliTest[1444:3417879] client: already connect(ing/ed) to FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:07:58.900 Thali,Test[1444:3417879] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 13:08:01.909 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:01.909 ThaliTest[1444:3417879] client: already connect(ing/ed) to FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:01.910 Thali,Test[1444:3417879] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 13:08:04.924 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:04.925 ThaliTest[1444:3417879] client: already connect(ing/ed) to FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:04.925 Thali,Test[1444:3417879] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 13:08:06.056 ThaliTest[1444:3417702] multipeer manager: restart client
,2016-03-21 13:08:06.070 ThaliTest[1444:3417702] client: found existing peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:08:07.944 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:07.945 ThaliTest[1444:3417879] client: already connect(ing/ed) to FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:07.945 Thali,Test[1444:3417879] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 13:08:10.957 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:10.957 ThaliTest[1444:3417879] client: already connect(ing/ed) to FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:10.958 ThaliTest[1444:3417879] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 13:08:13.975 ThaliTest[1444:3417879] jxcore: connect FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:13.975 ThaliTest[1444:3417879] client: already connect(ing/ed) to FE8F9526-AD74-40E1-9080-FD7FA9CC9893:8
2016-03-21 13:08:13.976 Thali,Test[1444:3417879] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 13:08:14.390 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 13:08:14.391 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 13:08:14.392 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:14.393 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
,2016-03-21 13:08:14.393 ThaliTest[1444:3417879] client session: disconnect
2016-03-21 13:08:14.393 ThaliTest[1444:3417879] client session: stateChange:1->0 FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:08:14.394 ThaliTest[1444:3417879] multipeer manager: stop client timer
2016-03-21 13:08:14.394 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-21 13:08:15.611 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:15.611 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:15.612 ThaliTest[1444:3,417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:15.613 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-21 13:08:16.068 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:16.068 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:16.069 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:16.071 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-21 13:08:16.598 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:16.599 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:16.599 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:16.600 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49915
,2016-03-21 13:08:16.718 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:16.719 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-21 13:08:16.721 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:16.723 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-21 13:08:16.848 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:16.849 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:08:16.849 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:08:16.849 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:08:16.850 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-21 13:08:16.942 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:16.944 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:16.945 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:16.947 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49917
,2016-03-21 13:08:17.222 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
2016-03-21 13:08:17.223 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 13:08:17.224 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 169 no errors
,2016-03-21 13:08:17.227 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 13:08:17.228 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,ok 170 still no errors
# setup
,2016-03-21 13:08:17.238 ThaliTest[1444:3417702] client: found new peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,DEBUG createPeerListener: createPeerListener
,DEBUG createPeerListener: pleaseConnect= 0
,2016-03-21 13:08:17.395 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:17.395 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:08:17.396 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:08:17.396 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
2016-03-21 13:08:17.396 ThaliTest[1444:3417879] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 13:08:17.397 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,# 43. should be able to call #startUpdateAdvertisingAndListening many times
,2016-03-21 13:08:17.581 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:17.582 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:17.582 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:17.584 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49920
,2016-03-21 13:08:17.796 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:08:17.796 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:10
2016-03-21 13:08:17.797 ThaliTest[1444:3417879] multipeer ,manager: start client restart timer: 0x16efbd50
2016-03-21 13:08:17.797 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:10
2016-03-21 13:08:17.797 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening: success
ok 171 no errors
,2016-03-21 13:08:17.799 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
2016-03-21 13:08:17.799 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:08:17.799 ThaliTest[1444:3417879] multipeer manager: stop client timer
,2016-03-21 13:08:17.800 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:11
,2016-03-21 13:08:17.801 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
2016-03-21 13:08:17.801 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:11
2016-03-21 13:08:17.802, ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening: success
ok 172 still no errors
# setup
,2016-03-21 13:08:17.826 ThaliTest[1444:3417702] client: found new peer: FE8F9526-AD74-40E1-9080-FD7FA9CC9893:9
,2016-03-21 13:08:17.979 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:17.979 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:08:17.980 ThaliTest[1444:3417879] multipeer manager: stop client timer
20,16-03-21 13:08:17.980 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
2016-03-21 13:08:17.980 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-21 13:08:17.982 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,# 44. should be able to call #stopAdvertisingAndListening many times
,2016-03-21 13:08:18.685 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:18.686 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:18.686 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:18.688 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49924
,2016-03-21 13:08:18.905 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:18.905 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:08:18.905 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
ok 173 no errors
,2016-03-21 13:08:18.906 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:18.907 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
,2016-03-21 13:08:18.907 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
,ok 174 still no errors
,# setup
,2016-03-21 13:08:19.217 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
2016-03-21 13:08:19.217 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
2016-03-21 13:08:19.217 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-21 13:08:19.218 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 13:08:19.219 ThaliTest[1444,:3417879] jxcore: stopListeningForAdvertisements: success
,# 45. can get the network status before starting
,2016-03-21 13:08:19.370 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 13:08:19.371 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:08:19.372 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:19.374 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 175 network status should have certain non-empty properties
,# setup
,# 46. error returned with bad router
,2016-03-21 13:08:20.792 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:20.793 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:20.793 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:20.795 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 176 specific error expected
,# setup
,# 47. all services are stopped when we call stop
,2016-03-21 13:08:21.552 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:21.552 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:21.553 ThaliTest[1444:3,417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:21.555 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49926
,2016-03-21 13:08:21.707 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements
,2016-03-21 13:08:21.708 ThaliTest[1444:3417879] multipeer manager: start client restart timer: 0x16efbd50
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 13:08:21.717 ThaliTest[1444:3417879] jxcore: startListeningForAdvertisements: success
,2016-03-21 13:08:21.720 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 13:08:21.722 ThaliTest[1444:3417879] server: starting ACF08CBB-018B-4F78-A189-81A63854F007:12
,2016-03-21 13:08:21.723 ThaliTest[1444:3417879] THEMultipeerManager initialized peer ACF08CBB-018B-4F78-A189-81A63854F007:12
2016-03-21 13:08:21.726 ThaliTest[1444:3417879] jxcore: startUpdateAdvertisingAndListening: success
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 177 connection to servers manager should succeed after starting
,ok 178 connection to router server should succeed after starting
,2016-03-21 13:08:21.774 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening
,2016-03-21 13:08:21.775 ThaliTest[1444:3417879] THEMultipeerManager stopping peer
,2016-03-21 13:08:21.776 ThaliTest[1444:3417879] jxcore: stopAdvertisingAndListening: success
,2016-03-21 13:08:21.777 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements
,2016-03-21 13:08:21.780 ThaliTest[1444:3417879] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 13:08:21.783 ThaliTest[1444:3417879] jxcore: stopListeningForAdvertisements: success
,DEBUG createNativeListener: mux close
,ok 179 is stopped after calling stop
,DEBUG createNativeListener: incoming socket close
,ok 180 connection to servers manager should fail after stopping
,ok 181 connection to router server should fail after stopping
,# setup
,# 48. make sure terminateConnection is properly hooked up
,2016-03-21 13:08:22.163 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:22.163 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:22.164 ThaliTest[1444:3417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:22.165 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 182 called with right arguments
,# setup
,# 49. make sure terminateListener is properly hooked up
,2016-03-21 13:08:22.618 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:22.618 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:22.619 ThaliTest[1444:3,417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:22.620 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 183 called with right arguments
,# setup
,# 50. make sure we actually call kill connections properly
,2016-03-21 13:08:22.956 ThaliTest[1444:3417879] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:08:22.957 ThaliTest[1444:3417879] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 13:08:22.957 ThaliTest[1444:3,417879] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:08:22.958 ThaliTest[1444:3417879] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,2016-03-21 13:08:23.033 ThaliTest[1444:3417879] Native method killConnections not found.

```
