#### Test 68102130f73255a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/D90C20D3-3C3E-4F0E-A031-15D122BC661F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D90C20D3-3C3E-4F0E-A031-15D122BC661F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/68102130f73255a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55213"
,(lldb)     command script import "/tmp/D90C20D3-3C3E-4F0E-A031-15D122BC661F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-29 10:09:27.020 ThaliTest[1372:4052124] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED6E2B06-B3A1-4DC9-BF6F-222B338E870A/Library/Cookies/Cookies.binarycookies
,2016-04-29 10:09:27.242 ThaliTest[1372:4052124] Apache Cordova native platform version 4.1.1 is starting.
,2016-04-29 10:09:27.243 ThaliTest[1372:4052124] Multi-tasking -> Device: YES, App: YES
,2016-04-29 10:09:27.256 ThaliTest[1372:4052124] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-29 10:09:28.064 ThaliTest[1372:4052124] Using UIWebView
,2016-04-29 10:09:28.066 ThaliTest[1372:4052124] [CDVTimer][handleopenurl] 0.132978ms
,2016-04-29 10:09:28.068 ThaliTest[1372:4052124] [CDVTimer][intentandnavigationfilter] 1.932025ms
2016-04-29 10:09:28.068 ThaliTest[1372:4052124] [CDVTimer][gesturehandler] 0.087023ms
2016-04-29 10:09:28.068 ThaliTest[1372:4052124] [CDVTimer][TotalPluginStartup] 2.574980ms
,2016-04-29 10:09:31.308 ThaliTest[1372:4052124] Resetting plugins due to page load.
,2016-04-29 10:09:32.698 ThaliTest[1372:4052124] Finished load of: file:///var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/index.html
,2016-04-29 10:09:32.833 ThaliTest[1372:4052124] JXcore Cordova plugin initializing
,2016-04-29 10:09:32.833 ThaliTest[1372:4052306] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-29 10:09:39.255 ThaliTest[1372:4052306] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-29 10:09:39.255 ThaliTest[1372:4052306] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-29 10:09:39.255 ThaliTest[1372:4,052306] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-29 10:09:39.257 ThaliTest[1372:4052306] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D79C7845-B670-4B3E-BF42-DC4975D577DE/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-29 10:09:44.379 ThaliTest[1372:4052124] THREAD WARNING: ['JXcore'] took '4848.212891' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55012
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55014
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
,DEBUG createNativeListener: listening 55017
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
,DEBUG createNativeListener: listening 55021
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
,DEBUG createNativeListener: listening 55026
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55030
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: listening 55034
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55038
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
,DEBUG createNativeListener: listening 55042
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,DEBUG createNativeListener: incoming socket close
,DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55094
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
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
,DEBUG createNativeListener: listening 55098
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
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
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
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
,# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
,# teardown
,# setup
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# teardown
,# setup
,# 19. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
,# setup
,# 20. basic
,ok 74 sane
,# teardown
,# setup
,# 21. another
,ok 75 sane
,# teardown
,# setup
,# 22. can pass data in setup
,[{"uuid":"831652d1-f5dc-4370-9bb4-e736119d075f","data":"custom data"},{"uuid":"b7ccdf89-53fb-4b69-acec-42a4f66f335f","data":"custom data"},{"uuid":"b7cd0fef-ad33-49c5-8781-858c9a5e3542","data":"custom data"},{"uuid":"f94a4309-984a-4df8-a677-f820db7183f0","data":"custom data"}]
ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
ok 84 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55108
,2016-04-29 10:12:45.529 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:45.529 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-29 10:12:45.531 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:45.531 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-29 10:12:45.921 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:45.921 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:12:45.921 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:12:45.921 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:45.922 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55110
,2016-04-29 10:12:46.145 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
2016-04-29 10:12:46.145 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:12:46.146 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
,2016-04-29 10:12:46.163 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-29 10:12:46.164 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-29 10:12:46.445 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:46.446 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:12:46.446 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:12:46.446 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
2016-04-29 10:12:46.446 ThaliTest[1372:4052306] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:12:46.447 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55112
,2016-04-29 10:12:46.989 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:12:46.989 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:1
,2016-04-29 10:12:46.989 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
2016-04-29 10:12:46.989 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:1
,2016-04-29 10:12:46.989 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-29 10:12:47.000 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
,2016-04-29 10:12:47.000 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
,2016-04-29 10:12:47.000 ThaliTest[1372:4052306] multipeer manager: stop client timer
,2016-04-29 10:12:47.001 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:2
2016-04-29 10:12:47.002 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
,2016-04-29 10:12:47.002 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:2
2016-04-29 10:12:47.002 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-29 10:12:48.009 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:12:48.009 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:12:48.009 ThaliTest[1372:4052306] multipeer manager: stop client timer
20,16-04-29 10:12:48.009 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:12:48.010 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:12:48.010 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55117
,2016-04-29 10:13:05.302 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:05.303 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:05.303 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: suc,cess
ok 109 error should be null
ok 110 error should be null
,2016-04-29 10:13:05.304 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:05.304 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:05.304 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
,# teardown
,2016-04-29 10:13:05.395 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:05.395 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:05.395 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:13:05.395 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:05.396 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55119
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-29 10:13:05.895 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:05.895 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:05.896 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
2016-04-29 10:13:05.896 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:05.896 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 55121
,2016-04-29 10:13:06.215 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
,2016-04-29 10:13:06.215 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:06.216 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
,2016-04-29 10:13:06.221 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:06.222 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:3
2016-04-29 10:13:06.222 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:3
2016-04-29 10:13:06.222 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-29 10:13:06.360 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:06.360 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:06.360 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-29 10:13:06.360 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:06.360 ThaliTest[1372:4052306] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:06.361 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
# teardown
,ok 130 error should be null
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
ok 133 port should match
,ok 134 host address should be null
ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-29 10:13:30.113 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
,2016-04-29 10:13:30.113 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:30.114 Th,aliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
,2016-04-29 10:13:30.114 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:30.115 ThaliTest[1372:4052306] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:30.115 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-29 10:13:30.361 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:30.361 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:30.362 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:30.362 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:30.362 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-29 10:13:30.945 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
2016-04-29 10:13:30.946 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:30.946 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
,ok 142 Can call startListeningForAdvertisements without error
2016-04-29 10:13:30.947 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-29 10:13:30.947 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-29 10:13:31.123 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
2016-04-29 10:13:31.123 ThaliTest[1372:4052306] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:31.125 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:31.125 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:31.126 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:31.126 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: suc,cess
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-29 10:13:31.939 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:31.939 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-29 10:13:31.940 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:31.941 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-29 10:13:38.245 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:13:38.246 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:38.246 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:38.247 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:38.247 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-29 10:13:48.570 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:48.570 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:4
,2016-04-29 10:13:48.570 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
2016-04-29 10:13:48.570 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:4
,2016-04-29 10:13:48.571 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:48.574 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:48.574 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:48.574 ThaliTest[1372:4052306] multipeer manager: stop client timer
2016-04-29 10:13:48.574 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:13:48.920 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-29 10:13:48.921 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:13:48.921 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:48.921 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:48.922 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-29 10:13:49.397 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:49.398 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:5
2016-04-29 10:13:49.398 ThaliTest[1372:4052306] multipeer m,anager: start client restart timer: 0x1458c5a0
2016-04-29 10:13:49.398 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:5
2016-04-29 10:13:49.398 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:49.399 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:13:49.399 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:49.399 ThaliTest[1372:4052306] multipeer manager: stop client timer
2016-04-29 10:13:49.399 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:6
2016-04-29 10:13:49.399 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
2016-04-29 10:13:49.400 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:6
2016-04-29 10:13:49.400 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-29 10:13:49.407 ThaliTest[1372:4052124] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
,2016-04-29 10:13:49.563 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-29 10:13:49.564 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-29 10:13:49.565 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
,2016-04-29 10:13:49.565 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
,2016-04-29 10:13:49.565 ThaliTest[1372:4052306] multipeer manager: stop client timer
2016-04-29 10:13:49.565 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-29 10:13:51.475 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:51.475 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:51.475 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:13:51.476 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:13:51.476 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:13:51.476 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-29 10:14:04.414 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:04.415 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:04.416 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:04.416 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
2016-04-29 10:14:04.416 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: suc,cess
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-29 10:14:09.983 ThaliTest[1372:4052306] jxcore: connect foo
2016-04-29 10:14:09.983 ThaliTest[1372:4052306] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
  ...
# teardown
,2016-04-29 10:14:10.155 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-29 10:14:10.156 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:14:10.157 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
,2016-04-29 10:14:10.157 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
,2016-04-29 10:14:10.157 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-29 10:14:10.484 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:10.484 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:7
,2016-04-29 10:14:10.485 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
2016-04-29 10:14:10.485 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:7
2016-04-29 10:14:10.485 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
,2016-04-29 10:14:10.486 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:14:10.487 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:10.490 ThaliTest[1372:4052124] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-29 10:14:12.189 ThaliTest[1372:4052124] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
,2016-04-29 10:14:12.654 ThaliTest[1372:4052124] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:2
,2016-04-29 10:14:13.593 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-29 10:14:13.593 ThaliTest[1372:405230,6] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-29 10:14:13.594 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:14:13.594 ThaliTest[1372:405230,6] THEMultipeerManager stopping peer
2016-04-29 10:14:13.594 ThaliTest[1372:4052306] multipeer manager: stop client timer
2016-04-29 10:14:13.594 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-29 10:14:32.186 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:14:32.186 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:8
,2016-04-29 10:14:32.186 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
2016-04-29 10:14:32.186 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:8
2016-04-29 10:14:32.186 ,ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
,2016-04-29 10:14:32.187 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-29 10:14:32.188 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-29 10:14:33.743 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:14:33.743 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:14:34.295 ThaliTest[1372:4052124] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7","pleaseConnect":0}]
2016-04-29 10:14:34.297 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:34.297 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:34.297 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:35.233 ThaliTest[1372:4052983] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:35.233 ThaliTest[1372:4052983] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:14:35.234 ThaliTest[1372:4052983] client session: disconnect
2016-04-29 10:14:35.234 ThaliTest[1372:4052983] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:35.235 ThaliTest[1372:4052983] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:35.235 ThaliTest[1372:4052983] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:14:38.241 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:38.242 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:38.242 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:38.400 ThaliTest[1372:4052982] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:38.400 ThaliTest[1372:4052982] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:14:38.400 ThaliTest[1372:4052982] client session: disconnect
2016-04-29 10:14:38.401 ThaliTest[1372:4052982] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:38.401 ThaliTest[1372:4052982] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:38.401 ThaliTest[1372:4052982] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:14:41.410 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:41.410 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:41.411 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:41.606 ThaliTest[1372:4052980] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:41.606 ThaliTest[1372:4052980] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:41.607 ThaliTest[1372:4052980] client session: disconnect
2016-04-29 10:14:41.607 ThaliTest[1372:4052980] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:41.607 ThaliTest[1372:4052980] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:41.608 ThaliTest[1372:4052980] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:14:44.044 ThaliTest[1372:4052124] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:2
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:2","pleaseConnect":0}]
,2016-04-29 10:14:44.615 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:44.615 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:44.615 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:44.732 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:14:44.732 ThaliTest[1372:4052124] server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
INFO testThaliMobileNative: Received pee,rAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:14:45.011 ThaliTest[1372:4053024] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:45.012 ThaliTest[1372:4053024] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:45.012 ThaliTest[1372:4053024] client session: disconnect
2016-04-29 10:14:45.012 ThaliTest[1372:4053024] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:45.012 ThaliTest[1372:4053024] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:45.012 ThaliTest[1372:4053024] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:14:45.345 ThaliTest[1372:4052124] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:7","pleaseConnect":0}]
,2016-04-29 10:14:46.213 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:14:46.213 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:14:46.213 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:14:48.019 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:48.019 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:14:48.019 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:48.283 ThaliTest[1372:4052980] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:48.284 ThaliTest[1372:4052980] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:48.284 ThaliTest[1372:4052980] client session: disconnect
2016-04-29 10:14:48.284 ThaliTest[1372:4052980] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:48.284 ThaliTest[1372:4052980] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:48.284 ThaliTest[1372:4052980] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:14:51.289 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:51.289 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:51.289 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:14:51.436 ThaliTest[1372:4053024] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:51.436 ThaliTest[1372:4053024] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:51.4,36 ThaliTest[1372:4053024] client session: disconnect
2016-04-29 10:14:51.437 ThaliTest[1372:4053024] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:51.437 ThaliTest[1372:4053024] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:51.437 ThaliTest[1372:4053024] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect ,retry - retries left: 4
,2016-04-29 10:14:52.187 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:14:52.194 ThaliTest[1372:4052124] client: found updated peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:14:52.194 ThaliTest[1372:4052124] client: found updated peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:52.194 ThaliTest[1372:4052124] client: found updated peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"DB1392E4-24A2-460A-8746-25C82246EF25:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvai,lable":1,"peerIdentifier":"DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":0}]
,2016-04-29 10:14:54.441 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:54.441 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:54.442 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:54.909 ThaliTest[1372:4053078] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:54.909 ThaliTest[1372:4053078] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:54.909 ThaliTest[1372:4053078] client session: disconnect
2016-04-29 10:14:54.909 ThaliTest[1372:4053078] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:54.910 ThaliTest[1372:4053078] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:54.910 ThaliTest[1372:4053078] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:14:57.741 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:14:57.741 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:14:57.741 ThaliTest[1372:4052124], server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:14:57.914 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:14:57.914 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:14:57.914 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:58.316 ThaliTest[1372:4053079] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:14:58.316 ThaliTest[1372:4053079] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:58.317 ThaliTest[1372:4053079] client session: disconnect
2016-04-29 10:14:58.317 ThaliTest[1372:4053079] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:14:58.318 ThaliTest[1372:4053079] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:14:58.318 ThaliTest[1372:4053079] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:14:59.220 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:14:59.221 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:14:59.221 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:15:01.323 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
,2016-04-29 10:15:01.323 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:15:01.323 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:01.395 ThaliTest[1372:4053079] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:01.395 ThaliTest[1372:4053079] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:15:01.395 ThaliTest[1372:4053079] client session: disconnect
2016-04-29 10:15:01.395 ThaliTest[1372:4053079] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:01.396 ThaliTest[1372:4053079] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:15:01.396 ThaliTest[1372:4053079] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:15:04.403 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:7
2016-04-29 10:15:04.404 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:15:04.404 ThaliTest[1372:4052306] client session: stateChange:0->,1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:04.527 ThaliTest[1372:4052982] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:04.528 ThaliTest[1372:4052982] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:15:04.528 ThaliTest[1372:4052982] client session: disconnect
2016-04-29 10:15:04.528 ThaliTest[1372:4052982] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:04.528 ThaliTest[1372:4052982] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:15:04.528 ThaliTest[1372:4052982] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
    operator: fail
  ...
,# teardown
,2016-04-29 10:15:10.915 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:15:10.915 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:15:10.915 ThaliTest[1372:4052124] server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:15:12.187 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:15:12.195 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:15:12.195 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:12.195 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:15:12.356 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:15:12.356 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:15:12.356 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:15:23.996 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:15:23.996 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
,2016-04-29 10:15:23.996 ThaliTest[1372:4052124] server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:15:25.506 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:15:25.506 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:15:25.506 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:15:32.187 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:15:32.195 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:15:32.195 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:15:32.196 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:15:37.149 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:15:37.149 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:15:37.149 ThaliTest[1372:4052124] server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:15:38.604 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:15:38.605 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:15:38.605 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:15:51.782 ThaliTest[1372:4052124] multipeer session: reset timer
,2016-04-29 10:15:51.782 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:15:51.782 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:15:52.187 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:15:52.195 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
2016-04-29 10:15:52.195 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:15:52.195 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,2016-04-29 10:16:04.501 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:16:04.501 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
,2016-04-29 10:16:04.501 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:16:05.879 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:16:05.879 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:16:05.880 ThaliTest[1372:4052124], server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:16:12.187 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:16:12.197 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:12.197 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:12.197 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:17.419 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:16:17.419 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:16:17.419 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:16:19.104 ThaliTest[1372:4052124] multipeer session: reset timer
,2016-04-29 10:16:19.104 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
,2016-04-29 10:16:19.104 ThaliTest[1372:4052124] server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:16:30.598 ThaliTest[1372:4052124] multipeer session: reset timer
,2016-04-29 10:16:30.599 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:16:30.599 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:8 != EF331042-C426-4B67-BF95-35460DC67D54:7)
,2016-04-29 10:16:31.752 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:16:31.752 ThaliTest[1372:4052124] server: disconnecting to refresh session (6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4)
2016-04-29 10:16:31.752 ThaliTest[1372:4052124], server: rejecting invitation for lexical ordering 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8","pleaseConnect":1}]
,2016-04-29 10:16:32.187 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:16:32.195 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:32.196 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
,2016-04-29 10:16:32.196 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:42.263 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-29 10:16:42.264 ThaliTest[1372:4052306] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-29 10:16:42.264 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening
2016-04-29 10:16:42.265 ThaliTest[1372:4052306] THEMultipeerManager stopping peer
,2016-04-29 10:16:42.266 ThaliTest[1372:4052306] multipeer manager: stop client timer
2016-04-29 10:16:42.266 ThaliTest[1372:4052306] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-29 10:16:44.560 ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening
2016-04-29 10:16:44.561 ThaliTest[1372:4052306] server: starting EF331042-C426-4B67-BF95-35460DC67D54:9
,2016-04-29 10:16:44.561 ThaliTest[1372:4052306] multipeer manager: start client restart timer: 0x1458c5a0
2016-04-29 10:16:44.561 ThaliTest[1372:4052306] THEMultipeerManager initialized peer EF331042-C426-4B67-BF95-35460DC67D54:9
2016-04-29 10:16:44.561 ,ThaliTest[1372:4052306] jxcore: startUpdateAdvertisingAndListening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-29 10:16:44.562 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-29 10:16:44.564 ThaliTest[1372:4052306] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-29 10:16:45.141 ThaliTest[1372:4052124] client: found new peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:45.141 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:45.142 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:16:45.142 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:45.712 ThaliTest[1372:4054354] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:45.712 ThaliTest[1372:4054354] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:45.712 ThaliTest[1372:4054354] client session: disconnect
2016-04-29 10:16:45.712 ThaliTest[1372:4054354] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:45.713 ThaliTest[1372:4054354] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:45.713 ThaliTest[1372:4054354] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative: Connect returned an error: Peer disconnected
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-29 10:16:45.963 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:16:45.964 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:9 != EF331042-C426-4B67-BF95-35460DC67D54:8)
,2016-04-29 10:16:47.079 ThaliTest[1372:4052124] client: found new peer: DB1392E4-24A2-460A-8746-25C82246EF25:8
2016-04-29 10:16:47.080 ThaliTest[1372:4052124] client: found new peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:8
,2016-04-29 10:16:48.716 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:48.716 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:16:48.716 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:49.373 ThaliTest[1372:4054382] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:49.374 ThaliTest[1372:4054382] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:49.374 ThaliTest[1372:4054382] client session: disconnect
2016-04-29 10:16:49.374 ThaliTest[1372:4054382] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:49.374 ThaliTest[1372:4054382] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:49.374 ThaliTest[1372:4054382] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-29 10:16:52.379 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:52.379 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:16:52.379 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:53.052 ThaliTest[1372:4054354] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:53.052 ThaliTest[1372:4054354] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:53.052 ThaliTest[1372:4054354] client session: disconnect
2016-04-29 10:16:53.052 ThaliTest[1372:4054354] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:53.052 ThaliTest[1372:4054354] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:53.053 ThaliTest[1372:4054354] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-29 10:16:56.054 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:56.054 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:16:56.054 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:56.716 ThaliTest[1372:4054354] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:56.716 ThaliTest[1372:4054354] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:16:56.716 ThaliTest[1372:4054354] client session: disconnect
2016-04-29 10:16:56.716 ThaliTest[1372:4054354] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:16:56.717 ThaliTest[1372:4054354] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:16:56.717 ThaliTest[1372:4054354] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-29 10:16:58.485 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:16:58.485 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:16:58.485 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:9 != EF331042-C426-4B67-BF95-35460DC67D54:8)
,2016-04-29 10:16:59.729 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:16:59.729 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:16:59.730 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:00.377 ThaliTest[1372:4054420] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:00.377 ThaliTest[1372:4054420] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:00.378 ThaliTest[1372:4054420] client session: disconnect
,2016-04-29 10:17:00.378 ThaliTest[1372:4054420] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:00.378 ThaliTest[1372:4054420] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:17:00.378 ThaliTest[1372:4054420] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-29 10:17:03.383 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:03.383 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:17:03.383 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:04.035 ThaliTest[1372:4054382] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:04.036 ThaliTest[1372:4054382] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:04.036 ThaliTest[1372:4054382] client session: disconnect
2016-04-29 10:17:04.036 ThaliTest[1372:4054382] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:04.036 ThaliTest[1372:4054382] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:04.036 ThaliTest[1372:4054382] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-29 10:17:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:17:04.569 ThaliTest[1372:4052124] client: found updated peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:17:04.569 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:04.569 ThaliTest[1372:4052124] client: found updated peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:07.043 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:07.043 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:17:07.043 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:07.201 ThaliTest[1372:4054383] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:07.202 ThaliTest[1372:4054383] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:07.202 ThaliTest[1372:4054383] client session: disconnect
,2016-04-29 10:17:07.202 ThaliTest[1372:4054383] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:07.202 ThaliTest[1372:4054383] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:07.202 ThaliTest[1372:4054383] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-29 10:17:10.209 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:10.209 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:17:10.209 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:10.326 ThaliTest[1372:4054420] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:10.326 ThaliTest[1372:4054420] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:10.326 ThaliTest[1372:4054420] client session: disconnect
2016-04-29 10:17:10.326 ThaliTest[1372:4054420] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:10.327 ThaliTest[1372:4054420] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:10.327 ThaliTest[1372:4054420] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-29 10:17:11.245 ThaliTest[1372:4052124] multipeer session: reset timer
,2016-04-29 10:17:11.245 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:17:11.245 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:9 != EF331042-C426-4B67-BF95-35460DC67D54:8)
,2016-04-29 10:17:13.339 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:13.339 ThaliTest[1372:4052306] client session: connect
2016-04-29 10:17:13.340 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:13.563 ThaliTest[1372:4054382] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:13.563 ThaliTest[1372:4054382] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:13.563 ThaliTest[1372:4054382] client session: disconnect
2016-04-29 10:17:13.563 ThaliTest[1372:4054382] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:13.563 ThaliTest[1372:4054382] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:13.564 ThaliTest[1372:4054382] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-29 10:17:16.574 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:16.575 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:17:16.575 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:17.166 ThaliTest[1372:4054430] client session: not connected DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:17.166 ThaliTest[1372:4054430] client session: onLinkFailure: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:17.167 ThaliTest[1372:4054430] client session: disconnect
,2016-04-29 10:17:17.167 ThaliTest[1372:4054430] client session: stateChange:1->0 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
,2016-04-29 10:17:17.167 ThaliTest[1372:4054430] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
2016-04-29 10:17:17.167 ThaliTest[1372:4054430] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,2016-04-29 10:17:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:17:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:8
2016-04-29 10:17:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:17:24.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:17:24.752 ThaliTest[1372:4052124] multipeer session: reset timer
2016-04-29 10:17:24.752 ThaliTest[1372:4052124] server: disconnecting to refresh session (DB4A2C0F-6E10-427C-8BF8-66B1948D1539)
2016-04-29 10:17:24.752 ThaliTest[1372:4052124] server: rejecting invitation from DB4A2C0F-6E10-427C-8BF8-66B1948D1539 due to previous generation (EF331042-C426-4B67-BF95-35460DC67D54:9 != EF331042-C426-4B67-BF95-35460DC67D54:8)
,2016-04-29 10:17:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:17:44.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:17:44.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:17:44.571 ThaliTest[1372:4052124] client: found updated peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:44.571 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:44.571 ThaliTest[1372:4052306] client session: connect
,2016-04-29 10:17:44.571 ThaliTest[1372:4052306] client session: stateChange:0->1 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:51.106 ThaliTest[1372:4054593] client session: p2p link connected
,2016-04-29 10:17:51.948 ThaliTest[1372:4054593] client session: stateChange:1->2 DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:51.948 ThaliTest[1372:4054593] client session: fireConnectCallback: DB4A2C0F-6E10-427C-8BF8-66B1948D1539
,2016-04-29 10:17:51.949 ThaliTest[1372:4054593] jxcore: connect: success
,2016-04-29 10:17:51.963 ThaliTest[1372:4052124] client: relay established
2016-04-29 10:17:51.963 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:17:51.963 ThaliTest[1372:4052124] client: new accepted socket: 0x16a098d0
2016-04-29 10:17:51.963 ThaliTest[1372:4052306] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:51.964 ThaliTest[1372:4052306] jxcore: connect: fail: Already connect(ing/ed)
,ok 182 Expected error
,ok 183 Null connection as expected
,2016-04-29 10:17:51.965 ThaliTest[1372:4052306] jxcore: connect DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:51.965 ThaliTest[1372:4052306] client: already connect(ing/ed) to DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:17:51.966 ThaliTest[1372:4052306] jxcore: connect: fail: Already connect(ing/ed)
,ok 184 Expected error
,ok 185 Null connection as expected
,# teardown
,2016-04-29 10:18:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:18:04.569 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:04.569 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:04.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:18:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:18:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:18:24.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:18:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:18:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:18:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:18:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:19:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:19:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:19:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:19:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:19:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:19:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:19:24.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:19:24.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:19:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:19:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:19:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:19:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:20:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:20:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:20:04.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:20:24.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:20:24.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:20:24.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:20:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:20:44.572 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:20:44.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:20:44.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:21:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:21:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:21:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:21:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:21:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:21:24.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:21:24.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:21:24.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:21:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:21:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:21:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:21:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:22:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:22:04.572 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:22:04.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:22:04.573 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:22:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:22:24.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:22:24.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:22:24.57,1 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:22:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:22:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:22:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:22:44.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:23:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:23:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:23:04.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:23:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:23:24.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:23:24.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:23:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:23:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:23:44.572 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:23:44.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:24:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:24:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:24:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:24:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:24:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:24:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:24:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:24:24.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:24:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:24:44.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:24:44.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:24:44.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:25:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:25:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:25:04.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:25:04.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:25:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:25:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:25:24.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:25:24.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:25:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:25:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:25:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:25:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:26:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:26:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:26:04.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:26:04.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:26:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:26:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:26:24.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:26:24.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:26:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:26:44.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:26:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:26:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:27:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:27:04.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:27:04.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:04.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:27:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:27:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:27:24.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:27:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:27:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:27:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:27:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:28:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:28:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:28:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:28:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:28:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:28:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:28:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:28:24.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:28:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:28:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:28:44.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:28:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:29:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:29:04.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:29:04.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:29:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:29:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:29:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:29:24.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:29:24.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:29:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:29:44.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:29:44.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:29:44.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:30:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:30:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:30:04.571 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:04.571 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
,2016-04-29 10:30:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:30:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:30:24.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:30:44.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:30:44.572 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
2016-04-29 10:30:44.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:30:44.572 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:31:04.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:31:04.571 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
,2016-04-29 10:31:04.572 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:31:04.572 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9
,2016-04-29 10:31:24.562 ThaliTest[1372:4052124] multipeer manager: restart client
,2016-04-29 10:31:24.570 ThaliTest[1372:4052124] client: found existing peer: DB1392E4-24A2-460A-8746-25C82246EF25:9
2016-04-29 10:31:24.570 ThaliTest[1372:4052124] client: found existing peer: 6697151F-D2B9-4AAF-BDF5-A8B1E9A452F4:9
2016-04-29 10:31:24.570 ThaliTest[1372:4052124] client: found existing peer: DB4A2C0F-6E10-427C-8BF8-66B1948D1539:9

```
