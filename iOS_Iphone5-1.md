#### Test 640346198400100_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CEBF618F-FE99-41F8-959F-CF4D054FF500/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/CEBF618F-FE99-41F8-959F-CF4D054FF500/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55550"
,(lldb)     command script import "/tmp/CEBF618F-FE99-41F8-959F-CF4D054FF500/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:01:19.314 ThaliTest[1601:3901272] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/21846CFF-F906-41FF-A422-E2C2231AE0B1/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:01:19.420 ThaliTest[1601:3901272] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:01:19.422 ThaliTest[1601:3901272] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:01:19.441 ThaliTest[1601:3901272] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:01:20.651 ThaliTest[1601:3901272] Using UIWebView
,2016-03-24 15:01:20.655 ThaliTest[1601:3901272] [CDVTimer][handleopenurl] 0.271022ms
,2016-03-24 15:01:20.660 ThaliTest[1601:3901272] [CDVTimer][intentandnavigationfilter] 4.517019ms
2016-03-24 15:01:20.660 ThaliTest[1601:3901272] [CDVTimer][gesturehandler] 0.243008ms
2016-03-24 15:01:20.660 ThaliTest[1601:3901272] [CDVTimer][TotalPluginStartup] 6.030977ms
,2016-03-24 15:01:25.090 ThaliTest[1601:3901272] Resetting plugins due to page load.
,2016-03-24 15:01:27.378 ThaliTest[1601:3901272] Finished load of: file:///var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/index.html
,2016-03-24 15:01:27.566 ThaliTest[1601:3901272] JXcore Cordova plugin initializing
2016-03-24 15:01:27.569 ThaliTest[1601:3901536] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:01:41.751 ThaliTest[1601:3901536] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-24 15:01:41.752 ThaliTest[1601:3901536] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 15:01:41.752 ThaliTest[1601:3,901536] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-03-24 15:01:41.756 ThaliTest[1601:3901536] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56AD7430-6672-4B61-B45F-43364C0A1E18/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,appEnteringBackground wasn't registered
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52052
ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52054
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
,DEBUG createNativeListener: listening 52057
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: 
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
,# teardown
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52061
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 52066
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 52070
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: incoming socket close
,ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52074
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52078
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 21 Buffers are identical
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
ok 27 The mux stream should be closed
DEBUG createNativeListener: incoming socket close
,# teardown
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52082
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
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new, incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new ,outgoing socket
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
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListene,r: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 52134
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
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
DEBUG createNativeListener: listening 52138
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
# teardown
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
ok 49 firstPromise result
ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
ok 52 secondPromise result
ok 53 secondPromise testValue
ok 54 thirdPromise in promise
,ok 55 thirdPromise result
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
,ok 84 error should be null
# setup
,# 23. #startUpdateAdvertisingAndListening should fail if start not called
,ok 85 specific error should be returned
# teardown
,ok 86 error should be null
ok 87 error should be null
# setup
,# 24. should be able to call #stopListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52150
,2016-03-24 15:04:19.633 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.634 ThaliTest[1601:39015,36] jxcore: stopListeningForAdvertisements: success
,ok 88 error should be null
ok 89 error should be null
2016-03-24 15:04:19.640 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.641 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements: success
,ok 90 error should be null
,ok 91 error should be null
,# teardown
,2016-03-24 15:04:19.727 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:19.727 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
2016-03-24 15:04:19.727 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:04:19.728 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:19.729 ThaliTest[1601,:3901536] jxcore: stopListeningForAdvertisements: success
ok 92 error should be null
,ok 93 error should be null
,# setup
,# 25. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52152
,2016-03-24 15:04:19.910 ThaliTest[1601:3901536] jxcore: startListeningForAdvertisements
,2016-03-24 15:04:19.912 ThaliTest[1601:3901536] multipeer manager: start client restart timer: 0x17673590
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-24 15:04:19.913 Th,aliTest[1601:3901536] jxcore: startListeningForAdvertisements: success
,ok 94 error should be null
ok 95 error should be null
2016-03-24 15:04:19.925 ThaliTest[1601:3901536] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryAct,ive":true}
2016-03-24 15:04:19.926 ThaliTest[1601:3901536] jxcore: startListeningForAdvertisements: success
ok 96 error should be null
ok 97 error should be null
# teardown
,2016-03-24 15:04:20.043 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:20.043 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
2016-03-24 15:04:20.043 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:04:20.044 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements
2016-03-24 15:04:20.044 ThaliTest[1601:3901536] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:20.045 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 98 error should be null
ok 99 error should be null
# setup
,# 26. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 52154
,2016-03-24 15:04:20.407 ThaliTest[1601:3901536] jxcore: startUpdateAdvertisingAndListening
2016-03-24 15:04:20.407 ThaliTest[1601:3901536] server: starting 3C663216-0910-4012-B61F-15D5E675ECB9:1
2016-03-24 15:04:20.408 ThaliTest[1601:3901536] multipeer m,anager: start client restart timer: 0x17673590
2016-03-24 15:04:20.408 ThaliTest[1601:3901536] THEMultipeerManager initialized peer 3C663216-0910-4012-B61F-15D5E675ECB9:1
2016-03-24 15:04:20.408 ThaliTest[1601:3901536] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 100 error should be null
,ok 101 error should be null
,2016-03-24 15:04:20.429 ThaliTest[1601:3901536] jxcore: startUpdateAdvertisingAndListening
,2016-03-24 15:04:20.430 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
,2016-03-24 15:04:20.432 ThaliTest[1601:3901536] multipeer manager: stop client timer
,2016-03-24 15:04:20.435 ThaliTest[1601:3901536] server: starting 3C663216-0910-4012-B61F-15D5E675ECB9:2
,2016-03-24 15:04:20.438 ThaliTest[1601:3901536] multipeer manager: start client restart timer: 0x17673590
2016-03-24 15:04:20.442 ThaliTest[1601:3901536] THEMultipeerManager initialized peer 3C663216-0910-4012-B61F-15D5E675ECB9:2
2016-03-24 15:04:20.443 ,ThaliTest[1601:3901536] jxcore: startUpdateAdvertisingAndListening: success
,ok 102 error should be null
,ok 103 error should be null
,# teardown
,2016-03-24 15:04:20.829 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:20.830 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
2016-03-24 15:04:20.830 ThaliTest[1601:3901536] multipeer manager: stop client timer
20,16-03-24 15:04:20.830 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening: success
2016-03-24 15:04:20.831 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:20.832 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 104 error should be null
ok 105 error should be null
# setup
,# 27. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 52159
,2016-03-24 15:04:27.018 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening
,2016-03-24 15:04:27.019 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
,2016-03-24 15:04:27.020 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening: success
,ok 106 error should be null
,ok 107 error should be null
,2016-03-24 15:04:27.023 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening
,2016-03-24 15:04:27.024 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
,2016-03-24 15:04:27.025 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening: success
,ok 108 error should be null
,ok 109 error should be null
,# teardown
,2016-03-24 15:04:44.718 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening
2016-03-24 15:04:44.718 ThaliTest[1601:3901536] THEMultipeerManager stopping peer
2016-03-24 15:04:44.719 ThaliTest[1601:3901536] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-24 15:04:44.719 ThaliTest[1601:3901536] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-24 15:04:44.720 ThaliTest[1601,:3901536] jxcore: stopListeningForAdvertisements: success
ok 110 error should be null
ok 111 error should be null
# setup

```
