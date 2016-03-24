#### Test 63968542e6bfc69_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63968542e6bfc69/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A58965EF-FC71-4CD1-B774-1AA68B6DB8D2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A58965EF-FC71-4CD1-B774-1AA68B6DB8D2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63968542e6bfc69/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63968542e6bfc69/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55896"
,(lldb)     command script import "/tmp/A58965EF-FC71-4CD1-B774-1AA68B6DB8D2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 21:14:01.860 ThaliTest[2200:3787116] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/75BCAC14-45F5-4637-84D7-66B5B28D8A5C/Library/Cookies/Cookies.binarycookies
,2016-03-24 21:14:02.119 ThaliTest[2200:3787116] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 21:14:02.121 ThaliTest[2200:3787116] Multi-tasking -> Device: YES, App: YES
,2016-03-24 21:14:02.140 ThaliTest[2200:3787116] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 21:14:02.960 ThaliTest[2200:3787116] Using UIWebView
2016-03-24 21:14:02.963 ThaliTest[2200:3787116] [CDVTimer][handleopenurl] 0.135005ms
,2016-03-24 21:14:02.967 ThaliTest[2200:3787116] [CDVTimer][intentandnavigationfilter] 3.808022ms
2016-03-24 21:14:02.967 ThaliTest[2200:3787116] [CDVTimer][gesturehandler] 0.160038ms
2016-03-24 21:14:02.967 ThaliTest[2200:3787116] [CDVTimer][TotalPluginS,tartup] 4.719019ms
,2016-03-24 21:14:06.243 ThaliTest[2200:3787116] Resetting plugins due to page load.
,2016-03-24 21:14:07.746 ThaliTest[2200:3787116] Finished load of: file:///var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/index.html
,2016-03-24 21:14:07.925 ThaliTest[2200:3787116] JXcore Cordova plugin initializing
,2016-03-24 21:14:07.927 ThaliTest[2200:3787287] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 21:14:16.217 ThaliTest[2200:3787287] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 21:14:16.217 ThaliTest[2200:3787287] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 21:14:16.218 ThaliTest[2200:3,787287] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 21:14:16.219 ThaliTest[2200:3787287] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F03D1636-1CC1-46C4-8F70-6E549A92DE6F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53041
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53043
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53046
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53050
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
DEBUG createNativeListener: listening 53055
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
,DEBUG createNativeListener: listening 53059
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
DEBUG createNativeListener: listening 53063
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53067
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed,
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53071
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeL,istener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 53123
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 32 Buffers are identical
,DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 53127
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
,# 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
,ok 47 Got the right error
# teardown
,# setup
,# 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
,# teardown
,# setup
,# 16. multiplex can send data
,ok 48 String should be length:200
,# teardown
,# setup
,# 17. enqueue and run in order
,ok 49 firstPromise setTimeout
,ok 50 firstPromise result
ok 51 firstPromise testValue
,ok 52 secondPromise setTimeout
ok 53 secondPromise result
ok 54 secondPromise testValue
ok 55 thirdPromise in promise
ok 56 thirdPromise result
ok 57 thirdPromise testValue
,# teardown
,# setup
,# 18. enqueueAtTop and run backwards
,ok 58 thirdPromise - first to run
ok 59 thirdPromise - in resolve
ok 60 secondPromise - second to run
ok 61 secondPromise - in catch
ok 62 firstPromise - third to run
ok 63 firstPromise - in then
ok 64 testing promises
# teardown
,# setup
,# 19. mix enqueue and enqueueAtTop
,ok 65 fourth
ok 66 fourth
ok 67 second
ok 68 secondPromise - in then
,ok 69 first
,ok 70 firstPromise - in catch
ok 71 third
ok 72 thirdPromise - in then
ok 73 testingPromises
# teardown
,# setup
,# 20. queues handled independently
,ok 74 all short operations completed before the long resolves
,# teardown
,# setup
,# 21. basic
,ok 75 sane
# teardown
,# setup
,# 22. another
,ok 76 sane
,# teardown
,# setup
,# 23. can pass data in setup
,ok 77 test participant has uuid
ok 78 participant data matches
ok 79 test participant has uuid
ok 80 participant data matches
ok 81 test participant has uuid
ok 82 participant data matches
# teardown
,# setup
,# 24. #startListeningForAdvertisements should fail if start not called
,ok 83 specific error should be returned
# teardown
,ok 84 error should be null
ok 85 error should be null
# setup
,# 25. #startUpdateAdvertisingAndListening should fail if start not called
,ok 86 specific error should be returned
# teardown
,ok 87 error should be null
ok 88 error should be null
# setup
,# 26. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53139
2016-03-24 21:16:31.865 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false},
2016-03-24 21:16:31.866 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements: success
ok 89 error should be null
ok 90 error should be null
2016-03-24 21:16:31.867 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 21:16:31.868 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be, null
# teardown
,2016-03-24 21:16:31.962 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24 21:16:31.963 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:16:31.963 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 21:16:31.963 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 21:16:31.964 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements: success
ok 93 error should be null
ok 94 error should be null
# setup
,# 27. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53141
2016-03-24 21:16:32.296 ThaliTest[2200:3787287] jxcore: startListeningForAdvertisements
,2016-03-24 21:16:32.298 ThaliTest[2200:3787287] multipeer manager: start client restart timer: 0x17ef9130
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 21:16:32.299 ThaliTest[2200:3787287] jxcore: startListeningForAdvertisements: success
,ok 95 error should be null
ok 96 error should be null
,2016-03-24 21:16:32.431 ThaliTest[2200:3787287] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-24 21:16:32.432 ThaliTest[2200:3787287] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,# teardown
,2016-03-24 21:16:33.193 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24 21:16:33.193 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:16:33.194 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: success
2016-03-24 21:16:33.194 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
2016-03-24 21:16:33.194 ThaliTest[2200:3787287] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 21:16:33.195 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 99 error should be null
ok 100 error should be null
# setup
,# 28. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53143
,2016-03-24 21:16:35.884 ThaliTest[2200:3787287] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 21:16:35.885 ThaliTest[2200:3787287] server: starting 21E28DF0-4733-48DB-9742-E312D6110593:1
,2016-03-24 21:16:35.885 ThaliTest[2200:3787287] multipeer manager: start client restart timer: 0x17ef9130
2016-03-24 21:16:35.886 ThaliTest[2200:3787287] THEMultipeerManager initialized peer 21E28DF0-4733-48DB-9742-E312D6110593:1
2016-03-24 21:16:35.886 ThaliTest[2200:3787287] jxcore: startUpdateAdvertisingAndListening: success
,ok 101 error should be null
ok 102 error should be null
,2016-03-24 21:16:35.943 ThaliTest[2200:3787287] jxcore: startUpdateAdvertisingAndListening
2016-03-24 21:16:35.943 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:16:35.943 ThaliTest[2200:3787287] multipeer manager: stop client timer
2016-03-24 21:16:35.943 ThaliTest[2200:3787287] server: starting 21E28DF0-4733-48DB-9742-E312D6110593:2
2016-03-24 21:16:35.944 ThaliTest[2200:3787287] multipeer manager: start client restart timer: 0x17ef9130
2016-03-24 21:16:35.944 ThaliTest[2200:3787287] THEMultipeerManager initialized peer 21E28DF0-4733-48DB-9742-E312D6110593:2
2016-03-24 21:16:35.944 ThaliTest[2200:3787287] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,# teardown
,2016-03-24 21:16:36.031 ThaliTest[2200:3787116] client: found new peer: ED8B76B9-142A-4D88-96CE-6633451B333B:2
,2016-03-24 21:16:40.352 ThaliTest[2200:3787116] client: found new peer: B27F167F-D7C3-4430-8125-4116A62F7B0E:2
,2016-03-24 21:16:49.662 ThaliTest[2200:3787116] client: lost peer: B27F167F-D7C3-4430-8125-4116A62F7B0E
2016-03-24 21:16:49.662 ThaliTest[2200:3787116] client session: onPeerLost: B27F167F-D7C3-4430-8125-4116A62F7B0E
,2016-03-24 21:16:55.945 ThaliTest[2200:3787116] multipeer manager: restart client
,2016-03-24 21:16:55.955 ThaliTest[2200:3787116] client: found existing peer: ED8B76B9-142A-4D88-96CE-6633451B333B:2
,2016-03-24 21:17:12.126 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24 21:17:12.126 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:17:12.126 ThaliTest[2200:3787287] multipeer manager: stop client timer
20,16-03-24 21:17:12.126 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: success
2016-03-24 21:17:12.127 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 21:17:12.127 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 105 error should be null
,ok 106 error should be null
,# setup
,# 29. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53148
2016-03-24 21:17:16.280 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24 21:17:16.280 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:17:16.280 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: success
ok 107 error should be null
ok 108 error should be null
2016-03-24 21:17:16.282 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24, 21:17:16.282 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:17:16.282 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
# teardown
,:3787287] jxcore: stopListeningForAdvertisements: success
ok 111 error should be null
ok 112 error should be null
# setup
2016-03-24 21:17:16.560 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24 21:17:16.560 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:17:16.561 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: success
2016-03-24 21:17:16.561 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 21:17:16.561 ThaliTest[2200,# 30. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 53150
ok 113 first call should succeed
ok 114 first call should succeed
ok 115 specific error should be returned
# teardown
,2016-03-24 21:17:17.058 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening
2016-03-24 21:17:17.058 ThaliTest[2200:3787287] THEMultipeerManager stopping peer
2016-03-24 21:17:17.058 ThaliTest[2200:3787287] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 21:17:17.058 ThaliTest[2200:3787287] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 21:17:17.059 ThaliTest[2200,:3787287] jxcore: stopListeningForAdvertisements: success
ok 116 error should be null
ok 117 error should be null
,# setup
,# 31. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 53152
2016-03-24 21:17:17.323 ThaliTest[2200:3787287] jxcore: startListeningForAdvertisements
2016-03-24 21:17:17.323 ThaliTest[2200:3787287] multipeer manager: start client restart timer: 0x17ef9130
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 21:17:17.324 ThaliTest[2200:3787287] jxcore: startListeningForAdvertisements: success
,2016-03-24 21:17:17.333 ThaliTest[2200:3787116] client: found new peer: ED8B76B9-142A-4D88-96CE-6633451B333B:2
,2016-03-24 21:17:17.354 ThaliTest[2200:3787287] jxcore: startUpdateAdvertisingAndListening

```
