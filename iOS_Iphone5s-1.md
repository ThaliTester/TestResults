#### Test 6391070405f2a33_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/344FF5BC-1FB1-4C55-9070-CD6445B4E1ED/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/344FF5BC-1FB1-4C55-9070-CD6445B4E1ED/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6391070405f2a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55610"
,(lldb)     command script import "/tmp/344FF5BC-1FB1-4C55-9070-CD6445B4E1ED/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:26:42.945 ThaliTest[2134:3743159] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/091465BE-2393-4C64-AD47-9453D1010C5D/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:26:43.203 ThaliTest[2134:3743159] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:26:43.204 ThaliTest[2134:3743159] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:26:43.223 ThaliTest[2134:3743159] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:26:44.042 ThaliTest[2134:3743159] Using UIWebView
,2016-03-24 15:26:44.046 ThaliTest[2134:3743159] [CDVTimer][handleopenurl] 0.167012ms
2016-03-24 15:26:44.049 ThaliTest[2134:3743159] [CDVTimer][intentandnavigationfilter] 2.638996ms
2016-03-24 15:26:44.049 ThaliTest[2134:3743159] [CDVTimer][gesturehandle,r] 0.119030ms
2016-03-24 15:26:44.049 ThaliTest[2134:3743159] [CDVTimer][TotalPluginStartup] 3.515005ms
,2016-03-24 15:26:47.304 ThaliTest[2134:3743159] Resetting plugins due to page load.
,2016-03-24 15:26:48.628 ThaliTest[2134:3743159] Finished load of: file:///var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/index.html
,2016-03-24 15:26:48.816 ThaliTest[2134:3743159] JXcore Cordova plugin initializing
2016-03-24 15:26:48.817 ThaliTest[2134:3743301] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:26:57.178 ThaliTest[2134:3743301] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 15:26:57.178 ThaliTest[2134:3743301] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 15:26:57.178 ThaliTest[2134:3743301] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 15:26:57.181 ThaliTest[2134:3743301] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81CC7ACB-5E86-459F-9CBF-9BE15C4ED5F4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52257
,ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52259
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
DEBUG createNativeListener: listening 52262
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
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
,DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52266
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
,# teardown
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52271
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 6. native server - closing incoming connection cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52275
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
DEBUG createNativeListener: listening 52279
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52283
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 52287
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
D,EBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creat,ing incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNat,iveListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG cr,eateNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DE,BUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBU,G createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
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
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG ,createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG creat,eNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG create,NativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52339
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
,ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52343
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be c,losed
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
,ok 63 testing promises
,# teardown
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
,# teardown
,# setup
,# 21. can pass data in setup
,ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
,# teardown
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
,# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52355
,2016-03-24 15:29:34.653 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:29:34.654 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
,ok 89 error should be null
,2016-03-24 15:29:34.656 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:29:34.657 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-24 15:29:34.784 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:34.784 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:29:34.784 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:29:34.785 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:34.786 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,ok 92 error should be null
ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52357
2016-03-24 15:29:35.039 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements
,2016-03-24 15:29:35.041 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:29:35.042 Th,aliTest[2134:3743301] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
,2016-03-24 15:29:35.081 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:29:35.082 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 15:29:35.306 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:35.307 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:29:35.307 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:29:35.307 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
2016-03-24 15:29:35.307 ThaliTest[2134:3743301] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:29:35.308 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
,# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52359
,2016-03-24 15:29:35.537 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:29:35.537 ThaliTest[2134:3743301] server: starting BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:1
,2016-03-24 15:29:35.538 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
2016-03-24 15:29:35.538 ThaliTest[2134:3743301] THEMultipeerManager initialized peer BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:1
2016-03-24 15:29:35.539 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening: success
,ok 100 error should be null
ok 101 error should be null
,2016-03-24 15:29:35.596 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:29:35.596 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:29:35.596 ThaliTest[2134:3743301] multipeer manager: stop client timer
2016-03-24 15:29:35.596 ThaliTest[2134:3743301] server: starting BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:2
2016-03-24 15:29:35.597 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
2016-03-24 15:29:35.597 ThaliTest[2134:,3743301] THEMultipeerManager initialized peer BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:2
2016-03-24 15:29:35.597 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-24 15:29:36.001 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:29:36.002 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:29:36.002 ThaliTest[2134:3743301] multipeer manager: stop client timer
20,16-03-24 15:29:36.002 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:29:36.002 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
,2016-03-24 15:29:36.003 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 104 error should be null
,ok 105 error should be null
,# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52364
2016-03-24 15:30:23.248 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:23.248 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:30:23.249 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
ok 107 error should be null
2016-03-24 15:30:23.250 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:23.251 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:30:23.251 ThaliT,est[2134:3743301] jxcore: stopAdvertisingAndListening: success
ok 108 error should be null
ok 109 error should be null
# teardown
,2016-03-24 15:30:46.277 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:46.277 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:30:46.277 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:30:46.278 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:46.278 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
# setup
,# 28. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52366
,ok 112 first call should succeed
,ok 113 first call should succeed
,ok 114 specific error should be returned
,# teardown
,2016-03-24 15:30:46.811 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:46.811 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:30:46.811 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:30:46.811 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:46.812 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,ok 115 error should be null
,ok 116 error should be null
,# setup
,# 29. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52368
,2016-03-24 15:30:47.119 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements
2016-03-24 15:30:47.119 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:47.120 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements: success
,2016-03-24 15:30:47.157 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:30:47.157 ThaliTest[2134:3743301] server: starting BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:3
2016-03-24 15:30:47.158 ThaliTest[2134:3743301] THEMultipeerManager initialized peer BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:3
2016-03-24 15:30:47.158 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening: success
,ok 117 called only once
ok 118 discovery state matches
ok 119 advertising state matches
,# teardown
,2016-03-24 15:30:47.460 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:47.461 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:30:47.461 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:30:47.461 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
2016-03-24 15:30:47.461 ThaliTest[2134:3743301] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:47.462 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,# setup
,# 31. can get the network status
,ok 126 network status should have certain non-empty properties
# teardown
,ok 127 error should be null
ok 128 error should be null
# setup
,# 32. wifi peer is marked unavailable if announcements stop
,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
,ok 129 host address should match
ok 130 port should match
,ok 131 host address should be null
ok 132 port should should be null
# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 133 error should be null
ok 134 error should be null
# setup
,# 33. Can call start/stopListeningForAdvertisements
,2016-03-24 15:30:54.505 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements
2016-03-24 15:30:54.506 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:54.507 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements: success
ok 135 Can call startListeningForAdvertisements without error
2016-03-24 15:30:54.508 ThaliTes,t[2134:3743301] jxcore: stopListeningForAdvertisements
2016-03-24 15:30:54.508 ThaliTest[2134:3743301] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:30:54.508 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
ok 136 Can call stopListeningForAdvertisements without error
# teardown
,2016-03-24 15:30:54.901 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:30:54.902 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-24 15:30:54.903 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:30:54.903 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:30:54.903 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 34. Calling startListeningForAdvertisements twice is NOT an error
,2016-03-24 15:30:55.525 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements
2016-03-24 15:30:55.526 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:55.526 ThaliTest[2134:3743301] jxcore: startListeningForAdvertisements: success
ok 139 Can call startListeningForAdvertisements without error
2016-03-24 15:30:55.527 ThaliTes,t[2134:3743301] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:30:55.528 ThaliTest[2134:3743301] jxcore: startListeningForAdv,ertisements: success
ok 140 Can call startListeningForAdvertisements twice without error
# teardown
,2016-03-24 15:31:15.527 ThaliTest[2134:3743159] multipeer manager: restart client
,2016-03-24 15:31:35.527 ThaliTest[2134:3743159] multipeer manager: restart client
,2016-03-24 15:31:55.527 ThaliTest[2134:3743159] multipeer manager: restart client
,2016-03-24 15:31:56.457 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
2016-03-24 15:31:56.457 ThaliTest[2134:3743301] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-24 15:31:56.459 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements: success
ok 141 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 15:31:56.460 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:31:56.461 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:31:56.461 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
ok 142 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Can call start/stopUpdateAdvertisingAndListening
,2016-03-24 15:32:05.251 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:32:05.251 ThaliTest[2134:3743301] server: starting BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:4
2016-03-24 15:32:05.251 ThaliTest[2134:3743301] multipeer manager: start client restart timer: 0x17da9d10
2016-03-24 15:32:05.251 ThaliTest[2134:3743301] THEMultipeerManager initialized peer BDCFC9AE-57C4-404D-85A3-609E0B92C9C7:4
2016-03-24 15:32:05.252 ThaliTest[2134:3743301] jxcore: startUpdateAdvertisingAndListening: success
ok 143 Can call startUpdateAdvertisingAndListening without error
2016-03-24 15:32:05.252 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:32:05.252 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
,2016-03-24 15:32:05.253 ThaliTest[2134:3743301] multipeer manager: stop client timer
2016-03-24 15:32:05.257 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
ok 144 Can call stopAdvertisingAndListening without error
# teardown
,2016-03-24 15:33:29.501 ThaliTest[2134:3743301] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:33:29.502 ThaliTest[2134:37433,01] jxcore: stopListeningForAdvertisements: success
ok 145 Should be able to call stopListeningForAdvertisments in teardown
2016-03-24 15:33:29.502 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening
2016-03-24 15:33:29.503 ThaliTest[2134:3743301] THEMultipeerManager stopping peer
2016-03-24 15:33:29.503 ThaliTest[2134:3743301] jxcore: stopAdvertisingAndListening: success
ok 146 Should be able to call stopAdvertisingAndListening in teardown
# setup

```
