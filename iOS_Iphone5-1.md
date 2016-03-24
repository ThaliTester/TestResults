#### Test 6391070405f2a33_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C89E980A-7D78-427D-8AB6-C7B6324CAC03/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/C89E980A-7D78-427D-8AB6-C7B6324CAC03/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55608"
,(lldb)     command script import "/tmp/C89E980A-7D78-427D-8AB6-C7B6324CAC03/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:26:12.494 ThaliTest[1612:3904868] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8D959C09-4E99-4E28-B60F-67125BC77F26/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:26:12.847 ThaliTest[1612:3904868] Apache Cordova native platform version 4.1.0 is starting.
2016-03-24 15:26:12.848 ThaliTest[1612:3904868] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:26:12.865 ThaliTest[1612:3904868] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:26:14.031 ThaliTest[1612:3904868] Using UIWebView
,2016-03-24 15:26:14.036 ThaliTest[1612:3904868] [CDVTimer][handleopenurl] 0.358999ms
2016-03-24 15:26:14.041 ThaliTest[1612:3904868] [CDVTimer][intentandnavigationfilter] 4.413009ms
2016-03-24 15:26:14.041 ThaliTest[1612:3904868] [CDVTimer][gesturehandler] 0.203967ms
2016-03-24 15:26:14.041 ThaliTest[1612:3904868] [CDVTimer][TotalPluginStartup] 5.891979ms
,2016-03-24 15:26:19.021 ThaliTest[1612:3904868] Resetting plugins due to page load.
,2016-03-24 15:26:20.799 ThaliTest[1612:3904868] Finished load of: file:///var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/index.html
,2016-03-24 15:26:21.039 ThaliTest[1612:3904868] JXcore Cordova plugin initializing
,2016-03-24 15:26:21.164 ThaliTest[1612:3904992] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:26:35.159 ThaliTest[1612:3904992] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 15:26:35.160 ThaliTest[1612:3904992] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-24 15:26:35.161 ThaliTest[1612:3904992] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 15:26:35.165 ThaliTest[1612:3904992] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/03A9BB66-BB01-48B8-AC3C-5D21FE6C1552/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52226
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52228
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52231
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52235
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52240
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52244
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
,# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52248
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52252
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52256
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
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
,DEBUG createNativeListener: listening 52308
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52312
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
,# teardown
,# setup
,# 12. closeAll can close even when connections open
,ok 45 not possible to connect to the server anymore
# teardown
,# setup
,# 13. closeAll with promise
,ok 46 not possible to connect to the server anymore
# teardown
,# setup
,# 14. multiplex can send data
,ok 47 String should be length:200
,# teardown
,# setup
,# 15. enqueue and run in order
,ok 48 firstPromise setTimeout
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
,# teardown
,# setup
,# 16. enqueueAtTop and run backwards
,ok 57 thirdPromise - first to run
ok 58 thirdPromise - in resolve
ok 59 secondPromise - second to run
ok 60 secondPromise - in catch
ok 61 firstPromise - third to run
ok 62 firstPromise - in then
ok 63 testing promises
# teardown
,# setup
,# 17. mix enqueue and enqueueAtTop
,ok 64 fourth
ok 65 fourth
ok 66 second
ok 67 secondPromise - in then
,ok 68 first
ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
# teardown
,# setup
,# 19. basic
,ok 74 sane
# teardown
,# setup
,# 20. another
,ok 75 sane
# teardown
,# setup
,# 21. can pass data in setup
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
# teardown
,# setup
,# 22. #startListeningForAdvertisements should fail if start not called
,ok 82 specific error should be returned
# teardown
,ok 83 error should be null
ok 84 error should be null
# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
,# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52324
2016-03-24 15:29:34.887 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false},
2016-03-24 15:29:34.888 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 15:29:34.891 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMob,ileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:34.892 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 15:29:35.015 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:35.015 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:29:35.016 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:29:35.016 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:35.017 ThaliTest[1612,:3904992] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52326
,2016-03-24 15:29:35.257 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements
,2016-03-24 15:29:35.259 ThaliTest[1612:3904992] multipeer manager: start client restart timer: 0x156bdb20
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:29:35.261 Th,aliTest[1612:3904992] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 15:29:35.272 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-24 15:29:35.273 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 15:29:35.530 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:35.530 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:29:35.530 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:29:35.531 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
2016-03-24 15:29:35.531 ThaliTest[1612:3904992] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:35.532 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52328
,2016-03-24 15:29:35.761 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:29:35.761 ThaliTest[1612:3904992] server: starting 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:1
2016-03-24 15:29:35.762 ThaliTest[1612:3904992] multipeer m,anager: start client restart timer: 0x156bdb20
2016-03-24 15:29:35.762 ThaliTest[1612:3904992] THEMultipeerManager initialized peer 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:1
2016-03-24 15:29:35.762 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
2016-03-24 15:29:35.775 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:29:35.775 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:29:35.775, ThaliTest[1612:3904992] multipeer manager: stop client timer
2016-03-24 15:29:35.775 ThaliTest[1612:3904992] server: starting 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:2
,2016-03-24 15:29:35.776 ThaliTest[1612:3904992] multipeer manager: start client restart timer: 0x156bdb20
2016-03-24 15:29:35.783 ThaliTest[1612:3904992] THEMultipeerManager initialized peer 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:2
2016-03-24 15:29:35.784 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
# teardown
,2016-03-24 15:29:36.231 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:36.231 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:29:36.231 ThaliTest[1612:3904992] multipeer manager: stop client timer
20,16-03-24 15:29:36.232 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:29:36.232 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:36.233 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52333
2016-03-24 15:30:09.151 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:09.151 ThaliTest[1612:3904992] THEMultipeerManager stoppi,ng peer
2016-03-24 15:30:09.152 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
ok 107 error should be null
,2016-03-24 15:30:09.154 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
,2016-03-24 15:30:09.155 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
,2016-03-24 15:30:09.155 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 15:30:43.526 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:43.527 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:30:43.527 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:30:43.527 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:43.528 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
,# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52335
,ok 112 first call should succeed
,ok 113 first call should succeed
ok 114 specific error should be returned
# teardown
,2016-03-24 15:30:47.038 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:47.038 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:30:47.038 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:30:47.039 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:47.039 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52337
2016-03-24 15:30:47.359 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements
2016-03-24 15:30:47.359 ThaliTest[1612:3904992] multipeer manager: start client restart timer: 0x156bdb20
DEBUG thaliMobi,leNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:47.360 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements: success
,2016-03-24 15:30:47.380 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:30:47.380 ThaliTest[1612:3904992] server: starting 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:3
2016-03-24 15:30:47.381 ThaliTest[1612:3904992] THEMultipee,rManager initialized peer 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:3
2016-03-24 15:30:47.381 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
# teardown
,2016-03-24 15:30:47.692 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:47.692 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:30:47.692 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:30:47.693 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
2016-03-24 15:30:47.693 ThaliTest[1612:3904992] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:47.694 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 120 error should be null
ok 121 error should be null
# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
ok 123 should not have been called more than once
,# teardown
,ok 124 error should be null
ok 125 error should be null
# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
# teardown
,ok 127 error should be null
,ok 128 error should be null
,# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
ok 130 port should match
,ok 131 host address should be null
ok 132 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 133 error should be null
ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 15:30:54.656 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements
2016-03-24 15:30:54.657 ThaliTest[1612:3904992] multipeer manager: start client restart timer: 0x156bdb20
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:54.658 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 15:30:54.659 ThaliTes,t[1612:3904992] jxcore: stopListeningForAdvertisements
2016-03-24 15:30:54.659 ThaliTest[1612:3904992] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-24 15:30:54.660 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 15:30:54.975 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:54.976 ThaliTest[1612:39049,92] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 15:30:54.977 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:54.977 ThaliTest[1612:390499,2] THEMultipeerManager stopping peer
2016-03-24 15:30:54.977 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 15:30:58.601 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements
2016-03-24 15:30:58.601 ThaliTest[1612:3904992] multipeer manager: start client restart timer: 0x156bdb20
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:58.602 ThaliTest[1612:3904992] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 15:30:58.603 ThaliTes,t[1612:3904992] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:58.604 ThaliTest[1612:3904992] jxcore: startListeningForAdv,ertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 15:31:18.520 ThaliTest[1612:3904868] multipeer manager: restart client
,2016-03-24 15:31:38.521 ThaliTest[1612:3904868] multipeer manager: restart client
,2016-03-24 15:31:40.329 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
2016-03-24 15:31:40.330 ThaliTest[1612:3904992] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-03-24 15:31:40.330 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 15:31:40.331 ThaliTest[1612:39049,92] jxcore: stopAdvertisingAndListening
2016-03-24 15:31:40.332 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
2016-03-24 15:31:40.332 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 15:32:23.214 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:32:23.214 ThaliTest[1612:3904992] server: starting 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:4
2016-03-24 15:32:23.215 ThaliTest[1612:3904992] multipeer m,anager: start client restart timer: 0x156bdb20
2016-03-24 15:32:23.215 ThaliTest[1612:3904992] THEMultipeerManager initialized peer 421CB6E9-DC61-4200-B1A5-DFB6B9C880D1:4
2016-03-24 15:32:23.215 ThaliTest[1612:3904992] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 15:32:23.216 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:32:23.217 ThaliTest[1612:3904992] THEMultipeerManager stopping peer
,2016-03-24 15:32:23.217 ThaliTest[1612:3904992] multipeer manager: stop client timer
2016-03-24 15:32:23.222 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
,# teardown
,2016-03-24 15:32:39.030 ThaliTest[1612:3904992] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:32:39.031 ThaliTest[1612:39049,92] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 15:32:39.031 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening
2016-03-24 15:32:39.032 ThaliTest[1612:390499,2] THEMultipeerManager stopping peer
2016-03-24 15:32:39.032 ThaliTest[1612:3904992] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,Disconnected from the test server
,Reconnected to the test server

```
