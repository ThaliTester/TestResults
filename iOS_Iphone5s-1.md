#### Test 681021307227906_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/4B2F9E22-AB1E-4780-BFE4-23BB712BB446/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4B2F9E22-AB1E-4780-BFE4-23BB712BB446/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/681021307227906/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55113"
,(lldb)     command script import "/tmp/4B2F9E22-AB1E-4780-BFE4-23BB712BB446/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-28 21:25:40.455 ThaliTest[3819:8913986] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2875AA36-378E-48E0-B2A5-C552B8E22B35/Library/Cookies/Cookies.binarycookies
,2016-04-28 21:25:40.819 ThaliTest[3819:8913986] Apache Cordova native platform version 4.1.1 is starting.
2016-04-28 21:25:40.820 ThaliTest[3819:8913986] Multi-tasking -> Device: YES, App: YES
,2016-04-28 21:25:40.844 ThaliTest[3819:8913986] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-28 21:25:41.867 ThaliTest[3819:8913986] Using UIWebView
,2016-04-28 21:25:41.874 ThaliTest[3819:8913986] [CDVTimer][handleopenurl] 0.265002ms
2016-04-28 21:25:41.878 ThaliTest[3819:8913986] [CDVTimer][intentandnavigationfilter] 3.871977ms
2016-04-28 21:25:41.879 ThaliTest[3819:8913986] [CDVTimer][gesturehandle,r] 0.182033ms
2016-04-28 21:25:41.879 ThaliTest[3819:8913986] [CDVTimer][TotalPluginStartup] 5.470037ms
,2016-04-28 21:25:46.974 ThaliTest[3819:8913986] Resetting plugins due to page load.
,2016-04-28 21:25:51.028 ThaliTest[3819:8913986] Finished load of: file:///var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/index.html
,2016-04-28 21:25:51.274 ThaliTest[3819:8913986] JXcore Cordova plugin initializing
2016-04-28 21:25:51.275 ThaliTest[3819:8914199] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-28 21:26:00.966 ThaliTest[3819:8914199] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-28 21:26:00.967 ThaliTest[3819:8914199] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-28 21:26:00.967 ThaliTest[3819:8,914199] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-04-28 21:26:00.970 ThaliTest[3819:8914199] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9F4A5C7E-91B1-403C-81D2-7BC54FE81AB1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-04-28 21:26:08.211 ThaliTest[3819:8913986] THREAD WARNING: ['JXcore'] took '6870.237061' ms. Plugin should use a background thread.
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65144
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65146
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
,DEBUG createNativeListener: listening 65149
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
,DEBUG createNativeListener: listening 65153
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
,DEBUG createNativeListener: listening 65158
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
,DEBUG createNativeListener: listening 65162
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
,DEBUG createNativeListener: listening 65166
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
,DEBUG createNativeListener: listening 65170
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
,DEBUG createNativeListener: listening 65174
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: listening 65226
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
,DEBUG createNativeListener: listening 65230
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
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
,# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. enqueue and run in order
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
,# 17. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# teardown
,# setup
,# 18. mix enqueue and enqueueAtTop
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
,[{"uuid":"12b0fe5c-5358-4bd1-a579-798f1c8d590d","data":"custom data"},{"uuid":"199e0e2c-9092-4104-af67-e71ad2ae16f8","data":"custom data"},{"uuid":"749167e2-4f0b-4861-8dc7-f1c6b8b47666","data":"custom data"},{"uuid":"76d70763-019d-486c-be48-b3480c768092",",data":"custom data"}]
,ok 76 test participant has uuid
,ok 77 participant data matches
,ok 78 test participant has uuid
,ok 79 participant data matches
,ok 80 test participant has uuid
,ok 81 participant data matches
,ok 82 test participant has uuid
,ok 83 participant data matches
,ok 84 own UUID is found from the participants list
,# teardown
,# setup
,# 23. #startListeningForAdvertisements should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,# setup
,# 24. #startUpdateAdvertisingAndListening should fail if start not called
,ok 88 specific error should be returned
,# teardown
,ok 89 error should be null
,ok 90 error should be null
,# setup
,# 25. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65240
,2016-04-28 21:27:54.160 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.162 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
,ok 92 error should be null
,2016-04-28 21:27:54.165 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:54.166 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-28 21:27:54.248 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:54.248 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:27:54.248 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:27:54.248 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:54.249 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65242
,2016-04-28 21:27:54.500 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
,2016-04-28 21:27:54.502 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:54.503 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-28 21:27:54.549 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:27:54.552 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-28 21:27:54.780 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:54.780 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:27:54.780 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
,2016-04-28 21:27:54.783 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
2016-04-28 21:27:54.783 ThaliTest[3819:8914199] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:27:54.786 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65244
,2016-04-28 21:27:55.314 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:27:55.315 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:1
2016-04-28 21:27:55.316 ThaliTest[3819:8914199] multipeer m,anager: start client restart timer: 0x166bd5f0
2016-04-28 21:27:55.316 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:1
2016-04-28 21:27:55.317 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-28 21:27:55.349 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:27:55.350 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:27:55.350 ThaliTest[3819:8914199] multipeer manager: stop client ti,mer
2016-04-28 21:27:55.351 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:2
,2016-04-28 21:27:55.353 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
2016-04-28 21:27:55.355 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:2
2016-04-28 21:27:55.355 ,ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-28 21:27:55.516 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:55.518 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:27:55.518 ThaliTest[3819:8914199] multipeer manager: stop client timer
2016-04-28 21:27:55.519 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: su,ccess
2016-04-28 21:27:55.519 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:27:55.521 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65249
,2016-04-28 21:27:56.591 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
,2016-04-28 21:27:56.592 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:27:56.593 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
,ok 110 error should be null
,2016-04-28 21:27:56.600 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:27:56.601 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:27:56.601 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
ok 111 error should be null
,ok 112 error should be null
,# teardown
,2016-04-28 21:28:01.941 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:01.941 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
,2016-04-28 21:28:01.941 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
2016-04-28 21:28:01.944 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:01.946 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
,ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65251
,ok 115 first call should succeed
,ok 116 first call should succeed
,ok 117 specific error should be returned
,# teardown
,2016-04-28 21:28:02.524 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:02.525 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:02.525 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-28 21:28:02.526 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:02.530 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 118 error should be null
,ok 119 error should be null
,# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 65253
,2016-04-28 21:28:02.733 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
2016-04-28 21:28:02.734 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:02.736 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,2016-04-28 21:28:02.791 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
,2016-04-28 21:28:02.793 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:3
2016-04-28 21:28:02.794 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:3
2016-04-28 21:28:02.795 Th,aliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
,# teardown
,2016-04-28 21:28:03.000 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:03.000 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:03.002 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
2016-04-28 21:28:03.003 ThaliTest[3819:8914199] jxcore: stopListeningForAdverti,sements
2016-04-28 21:28:03.003 ThaliTest[3819:8914199] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:28:03.005 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 123 error should be null
,ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
,ok 126 should not have been called more than once
,# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. can get the network status
,ok 129 network status should have certain non-empty properties
,# teardown
,ok 130 error should be null
,ok 131 error should be null
,# setup
,# 33. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 132 host address should match
,ok 133 port should match
,ok 134 host address should be null
,ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 136 error should be null
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-28 21:28:10.916 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
2016-04-28 21:28:10.917 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-28 21:28:10.919 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
2016-04-28 21:28:10.928 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:10.929 ThaliTest[3819:8914199] multipeer manager: stop client timer
DEBUG thaliMobileNa,tiveWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-28 21:28:10.933 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:11.230 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:11.233 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 140 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:11.237 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:11.237 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:11.238 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
ok 141 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-28 21:28:11.798 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
2016-04-28 21:28:11.799 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:11.803 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
,2016-04-28 21:28:11.806 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-28 21:28:11.810 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,ok 143 Can call startListeningForAdvertisements twice without error
,# teardown
,2016-04-28 21:28:15.280 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
2016-04-28 21:28:15.280 ThaliTest[3819:8914199] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:15.283 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-28 21:28:15.287 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:15.288 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:15.288 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-28 21:28:28.524 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.528 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 146 Can call stopListeningForAdvertisements without error
,2016-04-28 21:28:28.532 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.534 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 147 Can call stopListeningForAdvertisements without error
,# teardown
,2016-04-28 21:28:28.776 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:28.778 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:28.782 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:28.783 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:28.783 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-28 21:28:28.987 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:28.987 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:4
,2016-04-28 21:28:28.988 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
2016-04-28 21:28:28.989 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:4
2016-04-28 21:28:28.990 ,ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening: success
,ok 150 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:28.995 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:28.995 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
,2016-04-28 21:28:28.996 ThaliTest[3819:8914199] multipeer manager: stop client timer
2016-04-28 21:28:28.997 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
,ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-28 21:28:31.843 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:31.846 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:31.849 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:31.850 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:31.850 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-28 21:28:35.944 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:35.945 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:5
2016-04-28 21:28:35.946 ThaliTest[3819:8914199] multipeer m,anager: start client restart timer: 0x166bd5f0
2016-04-28 21:28:35.946 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:5
2016-04-28 21:28:35.947 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:35.950 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:28:35.951 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
,2016-04-28 21:28:35.952 ThaliTest[3819:8914199] multipeer manager: stop client timer
,2016-04-28 21:28:35.952 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:6
2016-04-28 21:28:35.954 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
2016-04-28 21:28:35.955 ThaliTest[3819:89141,99] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:6
2016-04-28 21:28:35.955 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-28 21:28:36.009 ThaliTest[3819:8913986] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:6
2016-04-28 21:28:36.010 ThaliTest[3819:8913986] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:6
,2016-04-28 21:28:36.011 ThaliTest[3819:8913986] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:6
,2016-04-28 21:28:36.084 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:28:36.086 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:36.090 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
,2016-04-28 21:28:36.091 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
,2016-04-28 21:28:36.097 ThaliTest[3819:8914199] multipeer manager: stop client timer
,2016-04-28 21:28:36.102 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-28 21:28:36.844 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.845 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:36.845 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
,ok 158 Can call startUpdateAdvertisingAndListening without error
,2016-04-28 21:28:36.850 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:36.851 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:36.851 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
ok 159 Can call stopAdvertisingAndListening without error
,# teardown
,2016-04-28 21:28:38.777 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:38.779 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 160 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:38.783 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:38.784 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:38.784 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: suc,cess
ok 161 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-28 21:28:56.778 ThaliTest[3819:8914199] jxcore: connect foo
2016-04-28 21:28:56.778 ThaliTest[3819:8914199] jxcore: connect: fail: Start browsing first
,not ok 162 got right error
,  ---
,    operator: equal
,    expected: 'startListeningForAdvertisements is not active'
,    actual:   'Start browsing first'
,  ...
,# teardown
,2016-04-28 21:28:57.106 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-28 21:28:57.109 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:28:57.113 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:28:57.113 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:28:57.113 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 41. peerAvailabilityChange is called
,2016-04-28 21:29:00.120 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:00.120 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:00.121 ThaliTest[3819:8914199] multipeer m,anager: start client restart timer: 0x166bd5f0
2016-04-28 21:29:00.122 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:7
2016-04-28 21:29:00.122 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-28 21:29:00.126 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-28 21:29:00.128 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,ok 166 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:01.720 ThaliTest[3819:8913986] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
2016-04-28 21:29:01.723 ThaliTest[3819:8913986] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
ok 167 peers must be an array
ok 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
,# teardown
,2016-04-28 21:29:02.174 ThaliTest[3819:8913986] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
,2016-04-28 21:29:03.954 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:29:03.956 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:29:03.960 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:29:03.960 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:29:03.961 ThaliTest[3819:8914199] multipeer manager: stop client timer
20,16-04-28 21:29:03.961 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-28 21:29:05.211 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:29:05.211 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:8
,2016-04-28 21:29:05.214 ThaliTest[3819:8914199] multipeer manager: start client restart timer: 0x166bd5f0
2016-04-28 21:29:05.215 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:8
2016-04-28 21:29:05.215 ,ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:29:05.219 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeW,rapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-04-28 21:29:05.223 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-28 21:29:06.148 ThaliTest[3819:8913986] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:06.149 ThaliTest[3819:8913986] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:7
INFO testThaliMobileNative: Rece,ived peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7","pleaseConnect":0}]
,2016-04-28 21:29:06.159 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:06.161 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:29:06.162 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:29:06.164 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"418CC5DB-B63A-41DA-9996-4D5D4125B76C:7","pleaseConnect":0}]
,2016-04-28 21:29:06.217 ThaliTest[3819:8913986] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:7","pleaseConnect":0}]
,2016-04-28 21:29:06.331 ThaliTest[3819:8913986] multipeer session: reset timer
,2016-04-28 21:29:06.332 ThaliTest[3819:8913986] server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:29:08.262 ThaliTest[3819:8914629] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:08.263 ThaliTest[3819:8914629] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:29:08.2,63 ThaliTest[3819:8914629] client session: disconnect
2016-04-28 21:29:08.263 ThaliTest[3819:8914629] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:08.264 ThaliTest[3819:8914629] client session: no connect callback (server initiated)
,2016-04-28 21:29:10.100 ThaliTest[3819:8913986] multipeer session: reset timer
2016-04-28 21:29:10.100 ThaliTest[3819:8913986] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
,2016-04-28 21:29:10.101 ThaliTest[3819:8913986] server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:29:13.635 ThaliTest[3819:8913986] multipeer session: reset timer
2016-04-28 21:29:13.635 ThaliTest[3819:8913986] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:29:13.636 ThaliTest[3819:8913986], server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:29:16.163 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:29:17.816 ThaliTest[3819:8913986] multipeer session: reset timer
,2016-04-28 21:29:17.817 ThaliTest[3819:8913986] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:29:17.819 ThaliTest[3819:8913986] server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:29:19.176 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:19.176 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:29:19.177 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:29:19.177 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
,2016-04-28 21:29:19.728 ThaliTest[3819:8914598] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:19.729 ThaliTest[3819:8914598] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:29:19.7,31 ThaliTest[3819:8914598] client session: disconnect
2016-04-28 21:29:19.731 ThaliTest[3819:8914598] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:19.733 ThaliTest[3819:8914598] client session: no connect callb,ack (server initiated)
,2016-04-28 21:29:21.967 ThaliTest[3819:8913986] multipeer session: reset timer
2016-04-28 21:29:21.967 ThaliTest[3819:8913986] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:29:21.968 ThaliTest[3819:8913986], server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:29:25.216 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:29:25.255 ThaliTest[3819:8913986] client: found updated peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:29:25.255 ThaliTest[3819:8913986] client: found updated peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:25.256 ,ThaliTest[3819:8913986] client: found updated peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"337492EA-97B4-404F-B8FE-E0E7631E59C8:8","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvai,lable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8","pleaseConnect":0}]
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"418CC5DB-B63A-41DA-9996-4D5D4125B76C:8","pleaseConnect":0}]
,2016-04-28 21:29:29.178 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:29:32.194 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:32.194 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:29:32.195 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:29:32.195 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:29:32.711 ThaliTest[3819:8914598] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:32.711 ThaliTest[3819:8914598] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:29:32.7,12 ThaliTest[3819:8914598] client session: disconnect
2016-04-28 21:29:32.712 ThaliTest[3819:8914598] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:29:32.715 ThaliTest[3819:8914598] client session: no connect callback (server initiated)
,2016-04-28 21:29:36.568 ThaliTest[3819:8913986] client: found new peer: FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"FE5DF0BC-D663-4C1F-B6BD-0E96835269BA:3","pleaseConnect":0}]
,2016-04-28 21:29:42.196 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:29:45.208 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:45.209 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:29:45.209 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:29:45.210 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:29:45.216 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:29:45.236 ThaliTest[3819:8913986] client: lost peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:29:45.238 ThaliTest[3819:8913986] client session: onPeerLost: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:29:45.239 ThaliTest[381,9:8913986] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:29:45.240 ThaliTest[3819:8913986] client session: disconnect
2016-04-28 21:29:45.242 ThaliTest[3819:8913986] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:29:45.245 ThaliTest[3819:8913986] client session: no connect callback (server initiated)
,2016-04-28 21:29:45.277 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:29:45.286 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:29:45.288 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8","pleaseConnect":0}]
,2016-04-28 21:29:55.210 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:29:58.221 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:29:58.222 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:29:58.223 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:29:58.223 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:29:58.495 ThaliTest[3819:8914808] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:58.496 ThaliTest[3819:8914808] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:29:58.498 ThaliTest[3819:8914808] client session: disconnect
,2016-04-28 21:29:58.498 ThaliTest[3819:8914808] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:29:58.500 ThaliTest[3819:8914808] client session: no connect callback (server initiated)
,2016-04-28 21:30:02.031 ThaliTest[3819:8913986] multipeer session: reset timer
2016-04-28 21:30:02.031 ThaliTest[3819:8913986] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:30:02.032 ThaliTest[3819:8913986], server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:30:05.216 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:30:05.258 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:30:05.258 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:05.25,9 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
,2016-04-28 21:30:08.224 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:30:11.230 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:30:11.231 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:30:11.231 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:30:11.232 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:12.095 ThaliTest[3819:8914808] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:12.097 ThaliTest[3819:8914808] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:30:12.0,97 ThaliTest[3819:8914808] client session: disconnect
2016-04-28 21:30:12.098 ThaliTest[3819:8914808] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:12.098 ThaliTest[3819:8914808] client session: no connect callb,ack (server initiated)
,2016-04-28 21:30:21.232 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-28 21:30:24.248 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:30:24.248 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:30:24.249 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:30:24.249 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:24.727 ThaliTest[3819:8914808] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:24.728 ThaliTest[3819:8914808] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:30:24.7,28 ThaliTest[3819:8914808] client session: disconnect
2016-04-28 21:30:24.728 ThaliTest[3819:8914808] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:24.729 ThaliTest[3819:8914808] client session: no connect callback (server initiated)
,2016-04-28 21:30:25.216 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:30:25.265 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:30:25.266 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:25.26,7 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:34.250 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:30:37.265 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:30:37.265 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:30:37.266 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:30:37.266 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:38.552 ThaliTest[3819:8914808] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:38.552 ThaliTest[3819:8914808] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:30:38.553 ThaliTest[3819:8914808] client session: disconnect
,2016-04-28 21:30:38.555 ThaliTest[3819:8914808] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:38.557 ThaliTest[3819:8914808] client session: no connect callback (server initiated)
,2016-04-28 21:30:41.692 ThaliTest[3819:8913986] multipeer session: reset timer
2016-04-28 21:30:41.693 ThaliTest[3819:8913986] server: disconnecting to refresh session (418CC5DB-B63A-41DA-9996-4D5D4125B76C)
2016-04-28 21:30:41.693 ThaliTest[3819:8913986], server: rejecting invitation from 418CC5DB-B63A-41DA-9996-4D5D4125B76C due to previous generation (30403743-C17E-454C-8124-9D59A7B25203:8 != 30403743-C17E-454C-8124-9D59A7B25203:7)
,2016-04-28 21:30:45.216 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:30:45.262 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:30:45.263 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:45.26,4 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:30:47.267 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:30:50.275 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:30:50.275 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:30:50.276 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:30:50.276 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:30:50.933 ThaliTest[3819:8914996] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:50.935 ThaliTest[3819:8914996] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:30:50.9,36 ThaliTest[3819:8914996] client session: disconnect
2016-04-28 21:30:50.936 ThaliTest[3819:8914996] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:30:50.937 ThaliTest[3819:8914996] client session: no connect callback (server initiated)
,2016-04-28 21:31:00.277 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:31:03.287 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:7
2016-04-28 21:31:03.288 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:31:03.289 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:31:03.289 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:03.508 ThaliTest[3819:8914996] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:03.509 ThaliTest[3819:8914996] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:03.509 ThaliTest[3819:8914996] client session: disconnect
,2016-04-28 21:31:03.510 ThaliTest[3819:8914996] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:03.514 ThaliTest[3819:8914996] client session: no connect callback (server initiated)
,2016-04-28 21:31:05.216 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:31:05.266 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
2016-04-28 21:31:05.268 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:31:05.26,9 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:13.290 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-28 21:31:18.397 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-28 21:31:18.399 ThaliTest[3819:8914199] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-28 21:31:18.403 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening
2016-04-28 21:31:18.404 ThaliTest[3819:8914199] THEMultipeerManager stopping peer
2016-04-28 21:31:18.404 ThaliTest[3819:8914199] multipeer manager: stop client timer
20,16-04-28 21:31:18.405 ThaliTest[3819:8914199] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-28 21:31:20.626 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndListening
2016-04-28 21:31:20.627 ThaliTest[3819:8914199] server: starting 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:31:20.628 ThaliTest[3819:8914199] multipeer m,anager: start client restart timer: 0x166bd5f0
2016-04-28 21:31:20.629 ThaliTest[3819:8914199] THEMultipeerManager initialized peer 30403743-C17E-454C-8124-9D59A7B25203:9
2016-04-28 21:31:20.629 ThaliTest[3819:8914199] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-28 21:31:20.632 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-28 21:31:20.634 ThaliTest[3819:8914199] jxcore: startListeningForAdvertisements: success
,ok 181 Can call startListeningForAdvertisements without error
,2016-04-28 21:31:22.145 ThaliTest[3819:8913986] client: found new peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:22.148 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:22.149 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:31:22.149 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:31:22.150 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:22.330 ThaliTest[3819:8913986] client: found new peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:8
2016-04-28 21:31:22.331 ThaliTest[3819:8913986] client: found new peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:8
,2016-04-28 21:31:24.584 ThaliTest[3819:8914996] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:24.585 ThaliTest[3819:8914996] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:24.5,86 ThaliTest[3819:8914996] client session: disconnect
2016-04-28 21:31:24.586 ThaliTest[3819:8914996] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:24.587 ThaliTest[3819:8914996] client session: no connect callback (server initiated)
,2016-04-28 21:31:32.151 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-28 21:31:35.160 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:35.161 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:31:35.161 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:31:35.162 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
,2016-04-28 21:31:35.994 ThaliTest[3819:8915103] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:35.996 ThaliTest[3819:8915103] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:31:35.9,96 ThaliTest[3819:8915103] client session: disconnect
2016-04-28 21:31:35.996 ThaliTest[3819:8915103] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:35.997 ThaliTest[3819:8915103] client session: no connect callb,ack (server initiated)
,2016-04-28 21:31:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:31:40.673 ThaliTest[3819:8913986] client: found updated peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:31:40.674 ThaliTest[3819:8913986] client: found updated peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:31:40.675 ,ThaliTest[3819:8913986] client: found updated peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:45.163 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-28 21:31:48.177 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:31:48.177 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:31:48.178 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:31:48.178 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:49.572 ThaliTest[3819:8915169] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:49.573 ThaliTest[3819:8915169] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
,2016-04-28 21:31:49.574 ThaliTest[3819:8915169] client session: disconnect
,2016-04-28 21:31:49.575 ThaliTest[3819:8915169] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:31:49.576 ThaliTest[3819:8915169] client session: no connect callback (server initiated)
,2016-04-28 21:31:58.179 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-28 21:32:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:32:00.669 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:32:00.670 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:00.684 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:01.194 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:01.195 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:32:01.196 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:32:01.196 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:02.137 ThaliTest[3819:8915212] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:02.138 ThaliTest[3819:8915212] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:32:02.140 ThaliTest[3819:8915212] client session: disconnect
,2016-04-28 21:32:02.140 ThaliTest[3819:8915212] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:02.144 ThaliTest[3819:8915212] client session: no connect callback (server initiated)
,2016-04-28 21:32:11.197 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-28 21:32:14.203 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:14.204 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:32:14.204 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:32:14.204 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:15.586 ThaliTest[3819:8915212] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:15.589 ThaliTest[3819:8915212] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:32:15.5,89 ThaliTest[3819:8915212] client session: disconnect
2016-04-28 21:32:15.590 ThaliTest[3819:8915212] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:15.591 ThaliTest[3819:8915212] client session: no connect callback (server initiated)
,2016-04-28 21:32:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:32:20.666 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:20.667 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:32:20.66,7 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:24.205 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-28 21:32:27.221 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:27.222 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:32:27.223 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:32:27.223 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:31.811 ThaliTest[3819:8915345] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:31.811 ThaliTest[3819:8915345] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:32:31.8,12 ThaliTest[3819:8915345] client session: disconnect
,2016-04-28 21:32:31.812 ThaliTest[3819:8915345] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:31.816 ThaliTest[3819:8915345] client session: no connect callback (server initiated)
,2016-04-28 21:32:37.224 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-28 21:32:40.236 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:40.237 ThaliTest[3819:8914199] client: server will connect
2016-04-28 21:32:40.238 ThaliTest[3819:8914199] client session: reverseConn,ect
2016-04-28 21:32:40.238 ThaliTest[3819:8914199] client session: stateChange:0->1 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:32:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:32:40.673 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:32:40.674 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:32:40.67,5 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:32:50.239 ThaliTest[3819:8913986] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-28 21:32:53.250 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:53.251 ThaliTest[3819:8914199] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:53.252 Thali,Test[3819:8914199] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-28 21:32:56.271 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:56.272 ThaliTest[3819:8914199] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:56.273 Thali,Test[3819:8914199] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-28 21:32:59.283 ThaliTest[3819:8914199] jxcore: connect C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:59.284 ThaliTest[3819:8914199] client: already connect(ing/ed) to C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:8
2016-04-28 21:32:59.284 Thali,Test[3819:8914199] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-28 21:33:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:33:00.681 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:00.682 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:33:00.68,3 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:33:13.242 ThaliTest[3819:8915372] client session: not connected C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:33:13.242 ThaliTest[3819:8915372] client session: onLinkFailure: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF
2016-04-28 21:33:13.2,43 ThaliTest[3819:8915372] client session: disconnect
2016-04-28 21:33:13.243 ThaliTest[3819:8915372] client session: stateChange:1->0 C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:33:13.244 ThaliTest[3819:8915372] client session: no connect callback (server initiated)
,2016-04-28 21:33:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:33:20.676 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:33:20.677 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:33:20.67,8 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:33:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:34:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:34:00.663 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:00.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:34:00.66,4 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:34:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:34:20.666 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:34:20.667 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:34:20.667 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:34:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:34:40.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:34:40.665 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:34:40.66,5 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:35:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:35:00.666 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:35:00.666 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:35:00.66,6 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:35:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:35:20.664 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:20.665 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:35:20.66,5 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:35:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:35:40.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:35:40.665 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:35:40.66,6 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:36:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:36:00.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:00.665 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:36:00.66,6 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:36:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:36:20.662 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:36:20.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:20.66,4 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:36:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:36:40.666 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:36:40.667 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:36:40.667 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:37:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:37:00.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:00.664 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:37:00.664 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:37:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:37:20.661 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:37:20.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:37:20.665 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:37:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:37:40.663 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:37:40.663 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:37:40.667 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:38:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:38:00.667 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:38:00.667 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:00.66,8 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:38:20.629 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:38:40.629 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:38:40.660 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:38:40.666 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:38:40.66,7 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:39:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:39:00.661 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:00.666 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:39:00.667 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:39:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:39:20.660 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:20.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:39:20.665 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:39:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:39:40.665 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:39:40.666 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:39:40.66,6 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:40:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:40:00.664 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:00.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:00.665 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:40:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:40:20.660 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:20.662 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:20.66,4 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:40:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:40:40.662 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:40:40.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:40:40.663 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:41:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:41:00.663 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:00.664 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:41:00.66,4 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:41:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:41:20.663 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:20.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:41:20.66,7 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:41:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:41:40.663 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:41:40.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:41:40.665 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:42:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:42:00.659 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:42:00.661 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:42:00.669 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:42:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:42:20.664 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:42:20.664 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:42:20.66,4 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:42:40.629 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:42:40.661 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:42:40.662 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:42:40.66,3 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:43:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:43:00.658 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:43:00.662 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:43:00.664 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:43:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:43:20.665 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:43:20.665 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:43:20.66,6 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:43:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:43:40.660 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:43:40.669 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:43:40.669 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:44:00.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:44:00.663 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:44:00.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:44:00.66,4 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:44:20.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:44:20.662 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:44:21.261 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:44:21.262 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:44:40.630 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:44:40.659 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:44:40.662 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:44:40.663 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:45:00.591 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:45:00.626 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:00.627 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:45:00.628 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:45:20.591 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:45:20.624 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:45:20.624 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:20.62,5 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:45:40.591 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:45:40.619 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:45:40.623 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:45:40.624 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:46:00.591 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:46:00.623 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:46:00.624 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:46:00.626 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
,2016-04-28 21:46:20.591 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:46:20.620 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:46:20.622 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
,2016-04-28 21:46:20.626 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:46:40.591 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:46:40.621 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:46:40.623 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9
2016-04-28 21:46:40.62,4 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
,2016-04-28 21:47:00.590 ThaliTest[3819:8913986] multipeer manager: restart client
,2016-04-28 21:47:00.624 ThaliTest[3819:8913986] client: found existing peer: C1CF11DB-5459-4FAE-B6AA-38A4A647C3FF:9
2016-04-28 21:47:00.625 ThaliTest[3819:8913986] client: found existing peer: 337492EA-97B4-404F-B8FE-E0E7631E59C8:9
2016-04-28 21:47:00.62,5 ThaliTest[3819:8913986] client: found existing peer: 418CC5DB-B63A-41DA-9996-4D5D4125B76C:9

```
