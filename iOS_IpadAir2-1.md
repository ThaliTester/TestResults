#### Test 62548124bd1cdb6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/301FA4B6-586C-4AEE-8667-E8B1A1328301/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/301FA4B6-586C-4AEE-8667-E8B1A1328301/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62548124bd1cdb6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53522"
,(lldb)     command script import "/tmp/301FA4B6-586C-4AEE-8667-E8B1A1328301/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-21 07:31:43.705 ThaliTest[1909:3213423] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7A251676-3397-48A4-97F5-E3650C861581/Library/Cookies/Cookies.binarycookies
,2016-03-21 07:31:44.062 ThaliTest[1909:3213423] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 07:31:44.063 ThaliTest[1909:3213423] Multi-tasking -> Device: YES, App: YES
,2016-03-21 07:31:44.082 ThaliTest[1909:3213423] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 07:31:45.943 ThaliTest[1909:3213423] Using UIWebView
,2016-03-21 07:31:45.949 ThaliTest[1909:3213423] [CDVTimer][handleopenurl] 0.385046ms
,2016-03-21 07:31:45.956 ThaliTest[1909:3213423] [CDVTimer][intentandnavigationfilter] 6.461024ms
,2016-03-21 07:31:45.957 ThaliTest[1909:3213423] [CDVTimer][gesturehandler] 0.333011ms
,2016-03-21 07:31:45.957 ThaliTest[1909:3213423] [CDVTimer][TotalPluginStartup] 8.737981ms
,2016-03-21 07:31:52.558 ThaliTest[1909:3213423] Resetting plugins due to page load.
,2016-03-21 07:31:55.711 ThaliTest[1909:3213423] Finished load of: file:///var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/index.html
,2016-03-21 07:31:55.918 ThaliTest[1909:3213423] JXcore Cordova plugin initializing
,2016-03-21 07:31:55.919 ThaliTest[1909:3213643] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 07:32:02.414 ThaliTest[1909:3213643] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 07:32:02.414 ThaliTest[1909:3213643] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 07:32:02.414 ThaliTest[1909:3213643] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:32:02.416 ThaliTest[1909:3213643] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/BB8E5413-1009-445E-A347-F215AD3B418F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 07:32:07.655 ThaliTest[1909:3213423] THREAD WARNING: ['JXcore'] took '4958.803711' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49858
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49860
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
,DEBUG createNativeListener: listening 49863
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
,DEBUG createNativeListener: listening 49867
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
,DEBUG createNativeListener: listening 49872
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
,DEBUG createNativeListener: listening 49876
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
,DEBUG createNativeListener: listening 49880
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
,DEBUG createNativeListener: listening 49884
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
,DEBUG createNativeListener: listening 49888
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
,DEBUG createNativeListener: listening 49940
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
,DEBUG createNativeListener: listening 49944
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
,DEBUG createNativeListener: listening 49956
,2016-03-21 07:36:16.310 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:16.313 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null
,ok 83 error should be null
,2016-03-21 07:36:16.320 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:16.322 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null
,ok 85 error should be null
,# setup
,2016-03-21 07:36:16.468 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:16.469 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:16.469 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:16.471 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:16.473 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49958
,2016-03-21 07:36:16.759 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,2016-03-21 07:36:16.761 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:36:16.764 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-21 07:36:16.791 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:36:16.793 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# setup
,2016-03-21 07:36:17.026 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:17.027 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:17.027 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:17.029 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,2016-03-21 07:36:17.030 ThaliTest[1909:3213643] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 07:36:17.034 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49960
,2016-03-21 07:36:17.557 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:17.558 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:1
,2016-03-21 07:36:17.560 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:36:17.560 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:1
2016-03-21 07:36:17.561 ,ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null
,ok 95 error should be null
,2016-03-21 07:36:17.594 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:17.594 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:17.595 ThaliTest[1909:3213643] multipeer manager: stop client timer
2016-03-21 07:36:17.596 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:2
2016-03-21 07:36:17.597 ThaliTest[1909:3213643] multipeer manager,: start client restart timer: 0x17dd6740
2016-03-21 07:36:17.597 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:2
2016-03-21 07:36:17.597 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 96 error should be null
ok 97 error should be null
,# setup
,2016-03-21 07:36:17.704 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:17.705 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:17.705 ThaliTest[1909:3213643] multipeer manager: stop client timer
,2016-03-21 07:36:17.706 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:17.709 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:17.713 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49965
,2016-03-21 07:36:18.249 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:18.250 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
2016-03-21 07:36:18.250 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-21 07:36:18.257 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:18.257 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:18.258 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# setup
,2016-03-21 07:36:19.213 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:19.214 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
2016-03-21 07:36:19.214 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:19.215 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:19.217 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49967
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,2016-03-21 07:36:23.017 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:23.017 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:23.018 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:23.019 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:23.021 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 49969
,2016-03-21 07:36:23.202 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,2016-03-21 07:36:23.203 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:36:23.209 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,2016-03-21 07:36:23.231 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:23.232 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:3
,2016-03-21 07:36:23.233 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:3
2016-03-21 07:36:23.233 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,2016-03-21 07:36:23.510 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:23.511 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:23.511 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:36:23.513 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,2016-03-21 07:36:23.515 ThaliTest[1909:3213643] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:23.517 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
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
,2016-03-21 07:36:28.877 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,2016-03-21 07:36:28.877 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:36:28.880 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:28.886 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,2016-03-21 07:36:28.887 ThaliTest[1909:3213643] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-21 07:36:28.891 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 07:36:29.156 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:29.158 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:29.161 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:29.161 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:29.162 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 07:36:29.641 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,2016-03-21 07:36:29.642 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:36:29.645 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:29.649 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:36:29.652 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 07:36:29.730 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,2016-03-21 07:36:29.731 ThaliTest[1909:3213643] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:29.735 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:29.738 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:29.738 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:29.739 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 07:36:30.261 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:30.262 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:4
,2016-03-21 07:36:30.264 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:36:30.264 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:4
2016-03-21 07:36:30.265 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 07:36:30.268 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
2016-03-21 07:36:30.268 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
2016-03-21 07:36:30.268 ThaliTest[1909:3213643] multipeer manager: stop client timer
20,16-03-21 07:36:30.269 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-21 07:36:30.385 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:36:30.387 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:30.390 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:30.391 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:30.391 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 07:36:31.310 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:31.311 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:5
,2016-03-21 07:36:31.312 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:36:31.313 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:5
,2016-03-21 07:36:31.314 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 07:36:31.317 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:31.317 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:31.318 ThaliTest[1909:3213643] multipeer manager: stop client timer
,2016-03-21 07:36:31.319 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:6
2016-03-21 07:36:31.320 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:36:31.320 ThaliTest[1909:32136,43] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:6
2016-03-21 07:36:31.320 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-21 07:36:31.389 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:36:31.391 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:31.394 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:31.395 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:31.397 ThaliTest[1909:3213643] multipeer manager: stop client timer
,2016-03-21 07:36:31.399 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 07:36:31.766 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:31.766 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:7
,2016-03-21 07:36:31.768 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:36:31.768 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:7
2016-03-21 07:36:31.768 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-21 07:36:31.772 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 07:36:31.774 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:33.058 ThaliTest[1909:3213423] client: found new peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 07:36:33.852 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:36:33.854 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:36:33.857 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:36:33.857 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:36:33.858 ThaliTest[1909:3213643] multipeer manager: stop client timer
2016-03-21 07:36:33.859 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 07:36:34.028 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:36:34.028 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:8
,2016-03-21 07:36:34.029 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:36:34.030 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:8
2016-03-21 07:36:34.030 ,ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 07:36:34.033 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 07:36:34.035 ThaliTest[1909:321364,3] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 07:36:35.040 ThaliTest[1909:3213423] client: found new peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7","pleaseConnect":0}]
,2016-03-21 07:36:35.045 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:35.046 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:36:35.047 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:35.135 ThaliTest[1909:3213423] client: lost peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:35.135 ThaliTest[1909:3213423] client session: onPeerLost: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:35.136 ThaliTest[1909:3213423] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:35.136 ThaliTest[1909:3213423] client session: disconnect
,2016-03-21 07:36:35.137 ThaliTest[1909:3213423] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:35.138 ThaliTest[1909:3213423] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:35.138 ThaliTest[1909:3213423] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 07:36:36.141 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7","pleaseConnect":0}]
,2016-03-21 07:36:36.265 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:36:36.266 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:36:38.153 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:38.153 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:36:38.154 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:38.241 ThaliTest[1909:3214182] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:38.242 ThaliTest[1909:3214182] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:38.242 ThaliTest[1909:3214182] client session: disconnect
,2016-03-21 07:36:38.242 ThaliTest[1909:3214182] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:38.244 ThaliTest[1909:3214182] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:38.244 ThaliTest[1909:3214182] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 07:36:41.253 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:41.254 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:36:41.254 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:41.861 ThaliTest[1909:3214219] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:41.862 ThaliTest[1909:3214219] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:41.862 ThaliTest[1909:3214219] client session: disconnect
,2016-03-21 07:36:41.864 ThaliTest[1909:3214219] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:41.866 ThaliTest[1909:3214219] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:41.866 ThaliTest[1909:3214219] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 07:36:44.874 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:44.875 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:36:44.875 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:45.792 ThaliTest[1909:3214144] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:45.792 ThaliTest[1909:3214144] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:45.7,92 ThaliTest[1909:3214144] client session: disconnect
2016-03-21 07:36:45.793 ThaliTest[1909:3214144] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:45.793 ThaliTest[1909:3214144] client session: fireConnectCallb,ack: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:45.794 ThaliTest[1909:3214144] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 07:36:48.208 ThaliTest[1909:3213423] multipeer session: reset timer
2016-03-21 07:36:48.209 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
,2016-03-21 07:36:48.209 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:36:48.801 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:48.802 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:36:48.802 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:48.914 ThaliTest[1909:3214219] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:48.914 ThaliTest[1909:3214219] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:48.916 ThaliTest[1909:3214219] client session: disconnect
2016-03-21 07:36:48.917 ThaliTest[1909:3214219] client session:, stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
2016-03-21 07:36:48.917 ThaliTest[1909:3214219] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:48.918 ThaliTest[1909:3214219] jxcore: connect: fail: Peer, disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 07:36:51.928 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:51.929 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:36:51.929 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:52.047 ThaliTest[1909:3214187] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:52.047 ThaliTest[1909:3214187] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:52.048 ThaliTest[1909:3214187] client session: disconnect
,2016-03-21 07:36:52.048 ThaliTest[1909:3214187] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:52.049 ThaliTest[1909:3214187] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:52.049 ThaliTest[1909:3214187] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 07:36:54.031 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:36:54.046 ThaliTest[1909:3213423] client: found updated peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8","pleaseConnect":0}]
,2016-03-21 07:36:55.061 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:55.062 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:36:55.062 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:36:55.190 ThaliTest[1909:3214187] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:36:55.190 ThaliTest[1909:3214187] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:36:55.192 ThaliTest[1909:3214187] client session: disconnect
2016-03-21 07:36:55.192 ThaliTest[1909:3214187] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:36:55.193 ThaliTest[1909:3214187] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:55.193 ThaliTest[1909:3214187] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 07:36:58.200 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:36:58.201 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:36:58.202 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:36:58.408 ThaliTest[1909:3214187] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:36:58.409 ThaliTest[1909:3214187] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:58.410 ThaliTest[1909:3214187] client session: disconnect
2016-03-21 07:36:58.410 ThaliTest[1909:3214187] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:36:58.411 ThaliTest[1909:3214187] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:36:58.411 ThaliTest[1909:3214187] jxcore: connect: fail: Peer, disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 07:37:01.319 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:37:01.320 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
,2016-03-21 07:37:01.320 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:37:01.417 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:37:01.418 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:37:01.418 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:37:01.508 ThaliTest[1909:3214187] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:37:01.509 ThaliTest[1909:3214187] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:37:01.509 ThaliTest[1909:3214187] client session: disconnect
,2016-03-21 07:37:01.509 ThaliTest[1909:3214187] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:37:01.511 ThaliTest[1909:3214187] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:37:01.511 ThaliTest[1909:3214187] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 07:37:04.523 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:7
,2016-03-21 07:37:04.524 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:37:04.524 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:37:04.633 ThaliTest[1909:3214303] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:37:04.634 ThaliTest[1909:3214303] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:37:04.634 ThaliTest[1909:3214303] client session: disconnect
2016-03-21 07:37:04.636 ThaliTest[1909:3214303] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:37:04.636 ThaliTest[1909:3214303] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:37:04.637 ThaliTest[1909:3214303] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 157 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 07:37:14.031 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:37:14.047 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:37:27.243 ThaliTest[1909:3213423] multipeer session: reset timer
2016-03-21 07:37:27.244 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
2016-03-21 07:37:27.244 ThaliTest[1909:3213423], server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:37:34.031 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:37:34.046 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:37:40.283 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:37:40.283 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
2016-03-21 07:37:40.284 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:37:53.368 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:37:53.368 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
,2016-03-21 07:37:53.369 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:37:54.031 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:37:54.046 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:06.420 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:38:06.420 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
,2016-03-21 07:38:06.421 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:38:14.031 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:38:14.045 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:19.585 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:38:19.585 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
2016-03-21 07:38:19.586 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to p,revious generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:38:32.240 ThaliTest[1909:3213423] multipeer session: reset timer
2016-03-21 07:38:32.240 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
2016-03-21 07:38:32.241 ThaliTest[1909:3213423], server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:8 != B601A2E8-785A-495E-A366-56984BFF195E:7)
,2016-03-21 07:38:34.031 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:38:34.044 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:42.238 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:38:42.240 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 158 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:38:42.243 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:38:42.243 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:38:42.244 ThaliTest[1909:3213643] multipeer manager: stop client timer
2016-03-21 07:38:42.244 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 159 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-21 07:38:42.497 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening
,2016-03-21 07:38:42.497 ThaliTest[1909:3213643] server: starting B601A2E8-785A-495E-A366-56984BFF195E:9
,2016-03-21 07:38:42.498 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
2016-03-21 07:38:42.499 ThaliTest[1909:3213643] THEMultipeerManager initialized peer B601A2E8-785A-495E-A366-56984BFF195E:9
2016-03-21 07:38:42.499 ThaliTest[1909:3213643] jxcore: startUpdateAdvertisingAndListening: success
,ok 160 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 07:38:42.501 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 07:38:42.504 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 161 Can call startListeningForAdvertisements without error
,2016-03-21 07:38:43.475 ThaliTest[1909:3213423] client: found new peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:43.477 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:43.477 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:38:43.479 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:44.216 ThaliTest[1909:3214878] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:44.216 ThaliTest[1909:3214878] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:38:44.217 ThaliTest[1909:3214878] client session: disconnect
,2016-03-21 07:38:44.217 ThaliTest[1909:3214878] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:44.220 ThaliTest[1909:3214878] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:38:44.220 ThaliTest[1909:3214878] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-03-21 07:38:44.552 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:38:44.553 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:9 != B601A2E8-785A-495E-A366-56984BFF195E:8)
,2016-03-21 07:38:47.227 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:47.229 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:38:47.229 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:47.811 ThaliTest[1909:3214878] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:38:47.812 ThaliTest[1909:3214878] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:38:47.812 ThaliTest[1909:3214878] client session: disconnect
,2016-03-21 07:38:47.812 ThaliTest[1909:3214878] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:47.815 ThaliTest[1909:3214878] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:38:47.816 ThaliTest[1909:3214878] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-03-21 07:38:50.823 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:38:50.824 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:38:50.824 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:50.962 ThaliTest[1909:3214940] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:38:50.964 ThaliTest[1909:3214940] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:38:50.9,64 ThaliTest[1909:3214940] client session: disconnect
2016-03-21 07:38:50.964 ThaliTest[1909:3214940] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:38:50.965 ThaliTest[1909:3214940] client session: fireConnectCallb,ack: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:38:50.965 ThaliTest[1909:3214940] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-03-21 07:38:53.974 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:53.975 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:38:53.976 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:54.128 ThaliTest[1909:3214938] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
2016-03-21 07:38:54.129 ThaliTest[1909:3214938] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:38:54.129 ThaliTest[1909:3214938] client session: disconnect
2016-03-21 07:38:54.131 ThaliTest[1909:3214938] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:54.131 ThaliTest[1909:3214938] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:38:54.132 ThaliTest[1909:3214938] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-03-21 07:38:56.732 ThaliTest[1909:3213423] multipeer session: reset timer
2016-03-21 07:38:56.733 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
,2016-03-21 07:38:56.733 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:9 != B601A2E8-785A-495E-A366-56984BFF195E:8)
,2016-03-21 07:38:57.138 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:57.139 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:38:57.140 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:57.230 ThaliTest[1909:3214938] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:57.231 ThaliTest[1909:3214938] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:38:57.231 ThaliTest[1909:3214938] client session: disconnect
,2016-03-21 07:38:57.232 ThaliTest[1909:3214938] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:38:57.233 ThaliTest[1909:3214938] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:38:57.233 ThaliTest[1909:3214938] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-03-21 07:39:00.241 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:00.242 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:39:00.242 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:00.415 ThaliTest[1909:3214940] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:00.418 ThaliTest[1909:3214940] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:00.418 ThaliTest[1909:3214940] client session: disconnect
2016-03-21 07:39:00.419 ThaliTest[1909:3214940] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:00.419 ThaliTest[1909:3214940] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:00.420 ThaliTest[1909:3214940] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-03-21 07:39:02.500 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:39:02.516 ThaliTest[1909:3213423] client: found updated peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:03.434 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:03.436 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:39:03.436 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:03.550 ThaliTest[1909:3214940] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:03.550 ThaliTest[1909:3214940] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:03.552 ThaliTest[1909:3214940] client session: disconnect
,2016-03-21 07:39:03.552 ThaliTest[1909:3214940] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:03.553 ThaliTest[1909:3214940] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:03.554 ThaliTest[1909:3214940] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-03-21 07:39:06.569 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:06.569 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:39:06.570 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:06.700 ThaliTest[1909:3214942] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
2016-03-21 07:39:06.701 ThaliTest[1909:3214942] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:06.701 ThaliTest[1909:3214942] client session: disconnect
,2016-03-21 07:39:06.701 ThaliTest[1909:3214942] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:06.702 ThaliTest[1909:3214942] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:39:06.703 ThaliTest[1909:3214942] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-03-21 07:39:09.696 ThaliTest[1909:3213423] multipeer session: reset timer
,2016-03-21 07:39:09.696 ThaliTest[1909:3213423] server: disconnecting to refresh session (9B21440C-B83C-4E2E-BFBC-CE747C07DB63)
,2016-03-21 07:39:09.697 ThaliTest[1909:3213423] server: rejecting invitation from 9B21440C-B83C-4E2E-BFBC-CE747C07DB63 due to previous generation (B601A2E8-785A-495E-A366-56984BFF195E:9 != B601A2E8-785A-495E-A366-56984BFF195E:8)
,2016-03-21 07:39:09.716 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:09.717 ThaliTest[1909:3213643] client session: connect
2016-03-21 07:39:09.718 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:09.940 ThaliTest[1909:3214942] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
2016-03-21 07:39:09.940 ThaliTest[1909:3214942] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
,2016-03-21 07:39:09.940 ThaliTest[1909:3214942] client session: disconnect
2016-03-21 07:39:09.941 ThaliTest[1909:3214942] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:09.943 ThaliTest[1909:3214942] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:09.943 ThaliTest[1909:3214942] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-03-21 07:39:12.959 ThaliTest[1909:3213643] jxcore: connect 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:8
,2016-03-21 07:39:12.960 ThaliTest[1909:3213643] client session: connect
,2016-03-21 07:39:12.961 ThaliTest[1909:3213643] client session: stateChange:0->1 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:13.114 ThaliTest[1909:3215003] client session: not connected 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
2016-03-21 07:39:13.114 ThaliTest[1909:3215003] client session: onLinkFailure: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:13.114 ThaliTest[1909:3215003] client session: disconnect
,2016-03-21 07:39:13.115 ThaliTest[1909:3215003] client session: stateChange:1->0 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:13.117 ThaliTest[1909:3215003] client session: fireConnectCallback: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63
2016-03-21 07:39:13.118 ThaliTest[1909:3215003] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative: Connect returned an error: Peer disconnected
,WARN testThaliMobileNative: Too many connect retries!
,not ok 162 Connect failed!
,  ---
,    operator: fail
,  ...
,# setup
,2016-03-21 07:39:22.500 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:39:22.515 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:42.500 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:39:42.512 ThaliTest[1909:3213423] client: found existing peer: 9B21440C-B83C-4E2E-BFBC-CE747C07DB63:9
,2016-03-21 07:39:50.683 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 07:39:50.685 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 163 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 07:39:50.688 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:39:50.688 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:39:50.689 ThaliTest[1909:3213643] multipeer manager: stop client timer
2016-03-21 07:39:50.692 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# 39. #startListeningForAdvertisements should fail if start not called
,2016-03-21 07:39:50.909 ThaliTest[1909:3213643] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:39:50.910 ThaliTest[1909:3213643] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 07:39:50.911 ThaliTest[1909:3213643] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:50.914 ThaliTest[1909:3213643] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 165 specific error should be returned
,# setup
,# 40. #startUpdateAdvertisingAndListening should fail if start not called
,2016-03-21 07:39:51.160 ThaliTest[1909:3213643] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:39:51.161 ThaliTest[1909:3213643] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 07:39:51.162 ThaliTest[1909:3213643] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:51.165 ThaliTest[1909:3213643] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,ok 166 specific error should be returned
,# setup
,# 41. should be able to call #stopListeningForAdvertisements many times
,2016-03-21 07:39:51.482 ThaliTest[1909:3213643] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:39:51.484 ThaliTest[1909:3213643] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 07:39:51.486 ThaliTest[1909:3213643] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:51.489 ThaliTest[1909:3213643] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50009
,2016-03-21 07:39:51.599 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:39:51.602 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 167 no errors
,2016-03-21 07:39:51.606 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:39:51.608 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,ok 168 still no errors
,# setup
,2016-03-21 07:39:51.733 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening
,2016-03-21 07:39:51.734 ThaliTest[1909:3213643] THEMultipeerManager stopping peer
,2016-03-21 07:39:51.734 ThaliTest[1909:3213643] jxcore: stopAdvertisingAndListening: success
,2016-03-21 07:39:51.736 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 07:39:51.738 ThaliTest[1909:3213643] jxcore: stopListeningForAdvertisements: success
,# 42. should be able to call #startListeningForAdvertisements many times
,2016-03-21 07:39:51.979 ThaliTest[1909:3213643] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-21 07:39:51.980 ThaliTest[1909:3213643] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 07:39:51.981 ThaliTest[1909:3213643] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 07:39:51.984 ThaliTest[1909:3213643] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,# teardown
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 50011
,2016-03-21 07:39:52.082 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,2016-03-21 07:39:52.083 ThaliTest[1909:3213643] multipeer manager: start client restart timer: 0x17dd6740
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-21 07:39:52.086 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 169 no errors
,2016-03-21 07:39:52.092 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 07:39:52.096 ThaliTest[1909:3213643] jxcore: startListeningForAdvertisements: success
,ok 170 still no errors
,# setup
,2016-03-21 07:40:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:40:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:40:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:41:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:41:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:41:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:42:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:42:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:42:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:43:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:43:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:43:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:44:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:44:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:44:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:45:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:45:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:45:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:46:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:46:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:46:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:47:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:47:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:47:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:48:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:48:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:48:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:49:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:49:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:49:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:50:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:50:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:50:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:51:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:51:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:51:52.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:52:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:52:32.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:52:52.086 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:53:12.085 ThaliTest[1909:3213423] multipeer manager: restart client
,2016-03-21 07:53:32.084 ThaliTest[1909:3213423] multipeer manager: restart client

```
