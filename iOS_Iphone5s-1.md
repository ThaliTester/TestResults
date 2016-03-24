#### Test 64065450860dd96_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/16847B01-FE88-4C5D-BBCA-3317BC256423/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/16847B01-FE88-4C5D-BBCA-3317BC256423/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55811"
,(lldb)     command script import "/tmp/16847B01-FE88-4C5D-BBCA-3317BC256423/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 18:23:42.614 ThaliTest[2185:3768404] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9023F2AC-36C0-48FB-917F-7FBC14316639/Library/Cookies/Cookies.binarycookies
,2016-03-24 18:23:42.869 ThaliTest[2185:3768404] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 18:23:42.870 ThaliTest[2185:3768404] Multi-tasking -> Device: YES, App: YES
,2016-03-24 18:23:42.891 ThaliTest[2185:3768404] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 18:23:43.724 ThaliTest[2185:3768404] Using UIWebView
,2016-03-24 18:23:43.728 ThaliTest[2185:3768404] [CDVTimer][handleopenurl] 0.164986ms
,2016-03-24 18:23:43.731 ThaliTest[2185:3768404] [CDVTimer][intentandnavigationfilter] 2.779007ms
2016-03-24 18:23:43.732 ThaliTest[2185:3768404] [CDVTimer][gesturehandler] 0.135005ms
2016-03-24 18:23:43.732 ThaliTest[2185:3768404] [CDVTimer][TotalPluginStartup] 3.779054ms
,2016-03-24 18:23:47.020 ThaliTest[2185:3768404] Resetting plugins due to page load.
,2016-03-24 18:23:48.329 ThaliTest[2185:3768404] Finished load of: file:///var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/index.html
,2016-03-24 18:23:48.510 ThaliTest[2185:3768404] JXcore Cordova plugin initializing
2016-03-24 18:23:48.510 ThaliTest[2185:3768560] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 18:23:56.802 ThaliTest[2185:3768560] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 18:23:56.803 ThaliTest[2185:3768560] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 18:23:56.803 ThaliTest[2185:3,768560] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 18:23:56.805 ThaliTest[2185:3768560] jxcore: didRegisterToNativ,e incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/8B71E993-9D71-4CB4-A1FF-2B3A09024A96/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52830
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52832
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52835
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52839
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
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
DEBUG createNativeListener: listening 52844
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
DEBUG createNativeListener: listening 52848
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52852
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
,DEBUG createNativeListener: listening 52856
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
,DEBUG createNativeListener: listening 52860
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 52912
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52916
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
,ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
ok 55 thirdPromise result
ok 56 thirdPromise testValue
# teardown
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
,ok 69 firstPromise - in catch
ok 70 third
ok 71 thirdPromise - in then
ok 72 testingPromises
# teardown
,# setup
,# 18. queues handled independently
,ok 73 all short operations completed before the long resolves
,# teardown
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
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52928
2016-03-24 18:26:30.350 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.351 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 88 error should be null
ok 89 error should be null
2016-03-24 18:26:30.352 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMob,ileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.353 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 90 error should be null
ok 91 error should be null
# teardown
,2016-03-24 18:26:30.495 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:30.496 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:30.496 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:30.496 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:30.497 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52930
2016-03-24 18:26:30.857 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
,2016-03-24 18:26:30.859 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:30.860 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-24 18:26:30.900 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:30.901 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 e,rror should be null
# teardown
,2016-03-24 18:26:31.229 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:31.229 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:31.229 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:31.229 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:31.229 ThaliTest[2185:3768560] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:31.231 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52932
,2016-03-24 18:26:31.839 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 18:26:31.840 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:1
,2016-03-24 18:26:31.841 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
2016-03-24 18:26:31.841 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:1
2016-03-24 18:26:31.841 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-24 18:26:31.899 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:31.899 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:31.900 ThaliTest[2185:3768560] multipeer manager: stop client ti,mer
2016-03-24 18:26:31.900 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:2
2016-03-24 18:26:31.900 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
2016-03-24 18:26:31.901 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:2
2016-03-24 18:26:31.901 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
ok 103 error should be null
,# teardown
,2016-03-24 18:26:32.276 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:32.277 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:32.277 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:26:32.277 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:32.277 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 18:26:32.278 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52937
2016-03-24 18:26:32.915 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:32.916 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:32.916 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 106 error should be null
ok 107 error should be null
2016-03-24 18:26:32.918 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24, 18:26:32.918 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:32.918 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 18:26:33.227 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.227 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:33.227 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:33.227 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:33.228 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52939
ok 112 first call should succeed
ok 113 first call should succeed
ok 114 specific error should be returned
# teardown
,2016-03-24 18:26:33.966 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:33.967 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:33.967 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 18:26:33.967 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:33.967 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
ok 116 error should be null
# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52941
2016-03-24 18:26:34.720 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
2016-03-24 18:26:34.721 ThaliTest[2185:3768560] multipeer manager: sta,rt client restart timer: 0x156f3f30
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:34.721 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
,2016-03-24 18:26:34.752 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:34.753 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:3
2016-03-24 18:26:34.753 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:3
2016-03-24 18:26:34.753 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
# teardown
,2016-03-24 18:26:34.913 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
,2016-03-24 18:26:34.913 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:34.913 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
2016-03-24 18:26:34.913 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:34.913 ThaliTest[2185:3768560] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 18:26:34.914 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 120 error should be null
,ok 121 error should be null
,# setup
,# 30. does not send duplicate availability changes
,ok 122 should be called once
,ok 123 should not have been called more than once
,# teardown
,ok 124 error should be null
ok 125 error should be null
# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
,# teardown
,ok 127 error should be null
ok 128 error should be null
# setup
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
,2016-03-24 18:26:56.978 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
2016-03-24 18:26:56.978 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:56.979 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 18:26:56.980 ThaliTes,t[2185:3768560] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:56.980 ThaliTest[2185:3768560] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive,":false}
2016-03-24 18:26:56.981 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
,# teardown
,2016-03-24 18:26:57.243 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:57.243 ThaliTest[2185:37685,60] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:57.244 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:57.244 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:57.245 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 18:26:57.756 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
2016-03-24 18:26:57.757 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26:57.760 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 18:26:57.761 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 18:26,:57.761 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 18:26:57.854 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
2016-03-24 18:26:57.854 ThaliTest[2185:3768560] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:57.855 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:26:57.855 ThaliTest[2185:37685,60] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:57.856 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:57.856 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdve,rtisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 18:26:59.497 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:26:59.498 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:4
2016-03-24 18:26:59.498 ThaliTest[2185:3768560] multipeer m,anager: start client restart timer: 0x156f3f30
2016-03-24 18:26:59.498 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:4
,2016-03-24 18:26:59.498 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:26:59.502 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016,-03-24 18:26:59.502 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:59.502 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:26:59.502 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 18:26:59.794 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 18:26:59.795 ThaliTest[2185:37685,60] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 18:26:59.796 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:26:59.796 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:26:59.797 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-03-24 18:27:00.568 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.568 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:5
2016-03-24 18:27:00.568 ThaliTest[2185:3768560] multipeer m,anager: start client restart timer: 0x156f3f30
2016-03-24 18:27:00.569 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:5
2016-03-24 18:27:00.569 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
ok 147 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:00.570 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:00.570 ThaliTest[2185:3768560] THEMultipeerManager stopping pee,r
,2016-03-24 18:27:00.570 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:27:00.574 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:6
2016-03-24 18:27:00.575 ThaliTest[2185:3768560] multipeer manager,: start client restart timer: 0x156f3f30
2016-03-24 18:27:00.575 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:6
2016-03-24 18:27:00.575 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
ok 148 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-03-24 18:27:00.850 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-24 18:27:00.851 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
,ok 149 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:00.852 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:00.852 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:2,7:00.852 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:27:00.852 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 150 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. peerAvailabilityChange is called
,2016-03-24 18:27:01.082 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:01.082 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:7
2016-03-24 18:27:01.083 ThaliTest[2185:3768560] multipeer m,anager: start client restart timer: 0x156f3f30
2016-03-24 18:27:01.083 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:7
2016-03-24 18:27:01.083 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening: success
ok 151 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-24 18:27:01.084 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-03-24 18:27:01.085 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 152 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:02.215 ThaliTest[2185:3768404] client: found new peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:7
ok 153 peers must be an array
,ok 154 peers must not be zero-length
,ok 155 peer must have peerIdentifier
,ok 156 peerIdentifier must be a string
,ok 157 peer must have peerAvailable
,ok 158 peer must have pleaseConnect
,# teardown
,2016-03-24 18:27:02.277 ThaliTest[2185:3768404] client: found new peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:7
,2016-03-24 18:27:07.116 ThaliTest[2185:3768404] client: lost peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:27:07.117 ThaliTest[2185:3768404] client session: onPeerLost: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:27:07.117 ThaliTest[218,5:3768404] client: lost peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA
2016-03-24 18:27:07.117 ThaliTest[2185:3768404] client session: onPeerLost: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA
,2016-03-24 18:27:21.084 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:27:26.455 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:26.456 ThaliTest[2185:376856,0] jxcore: stopListeningForAdvertisements: success
ok 159 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:26.457 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:27:26.457 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:27:26.457 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:27:26.457 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 160 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Can connect to a remote peer
,2016-03-24 18:27:40.991 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:40.991 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:40.992 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
2016-03-24 18:27:40.994 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:8
2016-03-24 18:27:40.994 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 161 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:40.995 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-03-24 18:27:40.995 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 162 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:42.732 ThaliTest[2185:3768404] multipeer session: reset timer
2016-03-24 18:27:42.733 ThaliTest[2185:3768404] server session: connect
2016-03-24 18:27:42.733 ThaliTest[2185:3768404] server session: stateChange:0->1 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
,2016-03-24 18:27:42.737 ThaliTest[2185:3768404] server: accepting invitation 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA
,2016-03-24 18:27:43.016 ThaliTest[2185:3768404] client: found new peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"97D5591E-C6A4-4162-A8B1-F55F8E21E,7AB:8","pleaseConnect":0}]
2016-03-24 18:27:43.017 ThaliTest[2185:3768404] client: found new peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
2016-03-24 18:27:43.017 ThaliTest[2185:3768560] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:43.018 ThaliTest[2185:3768560] client: server will connect
2016-03-24 18:27:43.018 ThaliTest[2185:3768560] client session: reverseConnect
2016-03-24 18:27:43.018 ThaliTest[2185:3768560] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E,21E7AB:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8","pleaseConnect":0}]
,2016-03-24 18:27:43.227 ThaliTest[2185:3769013] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:43.228 ThaliTest[2185:3769013] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:27:43.229 ThaliTest[2185:3769013] client session: disconnect
2016-03-24 18:27:43.229 ThaliTest[2185:3769013] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:43.229 ThaliTest[2185:3769013] client session: no connect callback (server initiated)
,2016-03-24 18:27:43.238 ThaliTest[2185:3768404] multipeer session: reset timer
2016-03-24 18:27:43.239 ThaliTest[2185:3768404] server session: connect
2016-03-24 18:27:43.239 ThaliTest[2185:3768404] server session: stateChange:0->1 97D5591E-C6A4-4162-A8B,1-F55F8E21E7AB:8
,2016-03-24 18:27:43.243 ThaliTest[2185:3768404] server: accepting invitation 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
,2016-03-24 18:27:45.666 ThaliTest[2185:3769012] server session: p2p link connected
,2016-03-24 18:27:46.060 ThaliTest[2185:3768404] server relay: connected (to port: 52950)
2016-03-24 18:27:46.060 ThaliTest[2185:3768404] server session: stateChange:1->2 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
,2016-03-24 18:27:46.506 ThaliTest[2185:3768921] server session: p2p link connected
,2016-03-24 18:27:46.514 ThaliTest[2185:3768404] server relay: connected (to port: 52950)
2016-03-24 18:27:46.515 ThaliTest[2185:3768404] server session: stateChange:1->2 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:46.515 ThaliTest[2185:376840,4] jxcore: connect: success
INFO testThaliMobileNative: 
ok 163 Must have listeningPort
ok 164 listeningPort must be a number
ok 165 Connection must have clientPort
ok 166 clientPort must be a number
ok 167 Connection must have serverPort
ok 168 serverPort must be a number
ok 169 reverse connection must have clientPort != 0
ok 170 reverse connection must have serverPort != 0
,# teardown
,2016-03-24 18:27:49.388 ThaliTest[2185:3769121] server session: not connected 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
,2016-03-24 18:27:49.748 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:27:49.749 ThaliTest[2185:376840,4] server relay: socket disconnected
2016-03-24 18:27:49.749 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
ok 171 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 18:27:49.750 ThaliTest[2185:3768560] ,jxcore: stopAdvertisingAndListening
2016-03-24 18:27:49.750 ThaliTest[2185:3768404] server relay: 0x16c592a0 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket close,d by remote peer} 
2016-03-24 18:27:49.750 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:27:49.750 ThaliTest[2185:3768560] server session: disconnect
2016-03-24 18:27:49.750 ThaliTest[2185:3768560] server session: stateChange:2,->0 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
2016-03-24 18:27:49.751 ThaliTest[2185:3768404] server relay: socket disconnected
2016-03-24 18:27:49.751 ThaliTest[2185:3768404] server relay: 0x17228e60 disconnected with error Error Domain=GCDAsyncSocketError,Domain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
2016-03-24 18:27:49.753 ThaliTest[2185:3768560] server session: disconnect
2016-03-24 18:27:49.753 ThaliTest[2185:3768560] server session: stateC,hange:2->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
,2016-03-24 18:27:49.764 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:27:49.765 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 172 Should be able to call stopAdvertisingAndListening in teardown
# set,up
,# 39. Can shift large amounts of data
,2016-03-24 18:27:50.875 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndListening
2016-03-24 18:27:50.875 ThaliTest[2185:3768560] server: starting 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:27:50.875 ThaliTest[2185:3768560] multipeer manager: start client restart timer: 0x156f3f30
2016-03-24 18:27:50.876 ThaliTest[2185:3768560] THEMultipeerManager initialized peer 14C3A3B7-F65B-4CDF-8939-7B9ED734B46B:9
2016-03-24 18:27:50.876 ThaliTest[2185:3768560] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 173 Can call startUpdateAdvertisingAndListening without error
2016-03-24 18:27:50.876 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-24 18:27:50.877 ThaliTest[2185:3768560] jxcore: startListeningForAdvertisements: success
ok 174 Can call startListeningForAdvertisements without error
,2016-03-24 18:27:51.623 ThaliTest[2185:3768404] client: found new peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:51.624 ThaliTest[2185:3768560] jxcore: connect 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:51.625 ThaliTest[2185:3768560] client: server will connect
2016-03-24 18:27:51.625 ThaliTest[2185:3768560] client session: reverseConnect
2016-03-24 18:27:51.625 ThaliTest[2185:3768560] client session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
,2016-03-24 18:27:51.659 ThaliTest[2185:3768404] client: found new peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:8
,2016-03-24 18:27:53.246 ThaliTest[2185:3769119] client session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
2016-03-24 18:27:53.246 ThaliTest[2185:3769119] client session: onLinkFailure: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
2016-03-24 18:27:53.246 ThaliTest[2185:3769119] client session: disconnect
2016-03-24 18:27:53.246 ThaliTest[2185:3769119] client session: stateChange:1->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:8
,2016-03-24 18:27:53.247 ThaliTest[2185:3769119] client session: no connect callback (server initiated)
,2016-03-24 18:27:53.252 ThaliTest[2185:3768404] multipeer session: reset timer
2016-03-24 18:27:53.252 ThaliTest[2185:3768404] server session: connect
2016-03-24 18:27:53.252 ThaliTest[2185:3768404] server session: stateChange:0->1 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:27:53.256 ThaliTest[2185:3768404] server: accepting invitation 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB
,2016-03-24 18:27:55.749 ThaliTest[2185:3769013] server session: p2p link connected
,2016-03-24 18:27:55.825 ThaliTest[2185:3768404] server relay: connected (to port: 52956)
2016-03-24 18:27:55.825 ThaliTest[2185:3768404] server session: stateChange:1->2 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:27:55.825 ThaliTest[2185:3768404] jxcore: connect: success
INFO testThaliMobileNative: 
INFO testThaliMobileNative: Reverse connection
,INFO testThaliMobileNative: reverseData
INFO testThaliMobileNative: reverseSend
,INFO testThaliMobileNative: reverseData
ok 175 received should match sent reverse
,# teardown
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-24 18:28:10.876 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:28:10.888 ThaliTest[2185:3768404] client: found updated peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:28:10.888 ThaliTest[2185:3768404] client: found updated peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-24 18:28:30.876 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:28:30.889 ThaliTest[2185:3768404] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
,2016-03-24 18:28:30.893 ThaliTest[2185:3768404] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-24 18:28:50.876 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:28:50.895 ThaliTest[2185:3768404] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:28:50.895 ThaliTest[2185:3768404] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,INFO testThaliMobileNative: reverseData
,2016-03-24 18:28:53.307 ThaliTest[2185:3768921] server session: not connected 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:10.877 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:29:10.895 ThaliTest[2185:3768404] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:29:10.895 ThaliTest[2185:3768404] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:30.876 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:29:30.890 ThaliTest[2185:3768404] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
2016-03-24 18:29:30.892 ThaliTest[2185:3768404] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:29:50.877 ThaliTest[2185:3768404] multipeer manager: restart client
,2016-03-24 18:29:50.895 ThaliTest[2185:3768404] client: found existing peer: 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
2016-03-24 18:29:50.895 ThaliTest[2185:3768404] client: found existing peer: 1CD2D13E-74CD-4DBE-AC77-A03D24A564FA:9
,2016-03-24 18:30:00.731 ThaliTest[2185:3768404] server relay: socket disconnected
2016-03-24 18:30:00.731 ThaliTest[2185:3768404] server relay: 0x16ecd380 disconnected with error Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer} 
,2016-03-24 18:30:00.732 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-24 18:30:00.733 ThaliTest[2185:3768560] jxcore: stopListeningForAdvertisements: success
,ok 176 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 18:30:00.734 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening
2016-03-24 18:30:00.734 ThaliTest[2185:3768560] THEMultipeerManager stopping peer
2016-03-24 18:30:00.734 ThaliTest[2185:3768560] server session: disconnect
2016-03-24 18:30:00.734 ThaliTest[2185:3768560] server session: stateChange:2->0 97D5591E-C6A4-4162-A8B1-F55F8E21E7AB:9
,2016-03-24 18:30:00.736 ThaliTest[2185:3768560] multipeer manager: stop client timer
2016-03-24 18:30:00.736 ThaliTest[2185:3768560] jxcore: stopAdvertisingAndListening: success
ok 177 Should be able to call stopAdvertisingAndListening in teardown
# setup

```
