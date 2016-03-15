#### Test 625481246b04bc0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8AB28168-E4EE-4359-99FB-FD9F7117F7C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8AB28168-E4EE-4359-99FB-FD9F7117F7C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49495"
,(lldb)     command script import "/tmp/8AB28168-E4EE-4359-99FB-FD9F7117F7C5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 12:45:04.884 ThaliTest[1462:2354620] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FA96646E-7FA0-408B-A5FB-21D2F9159661/Library/Cookies/Cookies.binarycookies
,2016-03-15 12:45:05.258 ThaliTest[1462:2354620] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 12:45:05.259 ThaliTest[1462:2354620] Multi-tasking -> Device: YES, App: YES
,2016-03-15 12:45:05.282 ThaliTest[1462:2354620] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 12:45:07.064 ThaliTest[1462:2354620] Using UIWebView
,2016-03-15 12:45:07.075 ThaliTest[1462:2354620] [CDVTimer][handleopenurl] 0.524998ms
,2016-03-15 12:45:07.084 ThaliTest[1462:2354620] [CDVTimer][intentandnavigationfilter] 7.959008ms
2016-03-15 12:45:07.085 ThaliTest[1462:2354620] [CDVTimer][gesturehandler] 0.422001ms
2016-03-15 12:45:07.085 ThaliTest[1462:2354620] [CDVTimer][TotalPluginS,tartup] 10.951996ms
,2016-03-15 12:45:13.481 ThaliTest[1462:2354620] Resetting plugins due to page load.
,2016-03-15 12:45:16.254 ThaliTest[1462:2354620] Finished load of: file:///var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/index.html
,2016-03-15 12:45:16.507 ThaliTest[1462:2354620] JXcore Cordova plugin initializing
,2016-03-15 12:45:16.510 ThaliTest[1462:2354821] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 12:45:32.427 ThaliTest[1462:2354821] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 12:45:32.429 ThaliTest[1462:2354821] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-15 12:45:32.429 ThaliTest[1462:2354821] jxcore: didRegisterToNative networkChanged
,2016-03-15 12:45:32.430 ThaliTest[1462:2354821] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/41BD70A3-54D9-4780-A671-25FFBCF1C09E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. calling createNativeListener directly rejects

,# teardown

,ok 1 Should throw

,# setup

,# 2. emits incomingConnectionState

,# teardown

,ok 2 initial connection state should be CONNECTED

,ok 3 final connection state should be DISCONNECTED

,# setup

,# 3. emits routerPortConnectionFailed

,# teardown

,ok 4 routerPortConnectionFailed is emitted

,# setup

,# 4. native server connections all up

,# teardown

,ok 5 Send/recvd #1 should be equal length

,ok 6 Send/recvd #1 should be same

,ok 7 Send/recvd #2 should be equal length

,ok 8 Send/recvd #2 should be same

,ok 9 Should be exactly 2 client sockets

,# setup

,# 5. native server - closing incoming stream cleans outgoing socket

,# teardown

,ok 10 socket shouldn't close until after stream

,ok 11 incoming remains open

,# setup

,# 6. native server - closing incoming connection cleans outgoing socket

,# teardown

,ok 12 we should not have gotten an error

,ok 13 socket shouldn't close until after incoming

,ok 14 incoming is cleaned up

,# setup

,# 7. native server - closing outgoing socket cleans associated mux stream

,# teardown

,ok 15 stream was closed

,ok 16 incoming should survive

,ok 17 mux should have no streams

,# setup

,# 8. native server - closing the whole server cleans everything up

,# teardown

,ok 18 we should not have gotten an error

,ok 19 Buffers are identical

,ok 20 native server is nulled out

,ok 21 native server should be closed

,ok 22 incoming has been removed

,ok 23 Incoming should be done

,ok 24 The mux object should be closed

,ok 25 The mux stream should be closed

,# setup

,# 9. native server - we can get a ton of connections and data through and still clean up the server completely

,# teardown

,ok 26 native server is nulled out

,ok 27 native server should be closed

,ok 28 incoming has been removed

,# setup

,# 10. native server - simulate mux failure, make sure everything is cleaned up

,# teardown

,ok 29 we should not have gotten an error

,ok 30 Buffers are identical

,ok 31 server should be fine

,ok 32 server should be open

,ok 33 incoming has been removed

,ok 34 The mux object should be closed

,ok 35 The mux stream should be closed

,# setup

,# 11. native server - timing out the incoming connection cleans everything up

,# teardown

,ok 36 we should not have gotten an error

,ok 37 Buffers are identical

,ok 38 server should be fine

,ok 39 server should be open

,ok 40 incoming has been removed

,ok 41 The mux object should be closed

,ok 42 The mux stream should be closed

,# setup

,# 12. closeAll can close even when connections open

,# teardown

,ok 43 not possible to connect to the server anymore

,# setup

,# 13. closeAll with promise

,# teardown

,ok 44 not possible to connect to the server anymore

,# setup

,# 14. multiplex can send data

,# teardown

,ok 45 String should be length:200

,# setup

,# 15. enqueue and run in order

,# teardown

,ok 46 firstPromise setTimeout

,ok 47 firstPromise result

,ok 48 firstPromise testValue

,ok 49 secondPromise setTimeout

,ok 50 secondPromise result

,ok 51 secondPromise testValue

,ok 52 thirdPromise in promise

,ok 53 thirdPromise result

,ok 54 thirdPromise testValue

,# setup

,# 16. enqueueAtTop and run backwards

,# teardown

,ok 55 thirdPromise - first to run

,ok 56 thirdPromise - in resolve

,ok 57 secondPromise - second to run

,ok 58 secondPromise - in catch

,ok 59 firstPromise - third to run

,ok 60 firstPromise - in then

,ok 61 testing promises

,# setup

,# 17. mix enqueue and enqueueAtTop

,# teardown

,ok 62 fourth

,ok 63 fourth

,ok 64 second

,ok 65 secondPromise - in then

,ok 66 first

,ok 67 firstPromise - in catch

,ok 68 third

,ok 69 thirdPromise - in then

,ok 70 testingPromises

,# setup

,# 18. queues handled independently

,# teardown

,ok 71 all short operations completed before the long resolves

,# setup

,# 19. basic

,# teardown

,ok 72 sane

,# setup

,# 20. another

,# teardown

,ok 73 sane

,# setup

,# 21. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 74 specific error should be returned

,# setup

,ok 75 error should be null

,ok 76 error should be null

,# 22. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 77 specific error should be returned

,# setup

,ok 78 error should be null

,ok 79 error should be null

,# 23. should be able to call #stopListeningForAdvertisements many times

,# teardown

,2016-03-15 12:48:38.357 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:38.361 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,ok 80 error should be null

,ok 81 error should be null

,2016-03-15 12:48:38.367 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:38.368 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null

,ok 83 error should be null

,# setup

,2016-03-15 12:48:38.490 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:38.492 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:38.492 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:48:38.494 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:38.495 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null

,ok 85 error should be null

,# 24. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-15 12:48:38.810 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
,2016-03-15 12:48:38.817 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
,2016-03-15 12:48:38.820 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements: success
,ok 86 error should be null

,ok 87 error should be null

,2016-03-15 12:48:38.853 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
,2016-03-15 12:48:38.857 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null

,ok 89 error should be null

,# setup
,
,2016-03-15 12:48:39.852 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:39.853 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:39.853 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: suc,cess
,2016-03-15 12:48:39.856 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
2016-03-15 12:48:39.857 ThaliTest[1462:2354821] multipeer manager: stop client timer
,2016-03-15 12:48:39.858 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 90 error should be null

,ok 91 error should be null

,# 25. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-15 12:48:40.698 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:48:40.700 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:1
,2016-03-15 12:48:40.701 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
2016-03-15 12:48:40.702 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:1
2016-03-15 12:48:40.703 ,ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening: success
,ok 92 error should be null

,ok 93 error should be null

,2016-03-15 12:48:40.754 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:48:40.755 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:40.756 ThaliTest[1462:2354821] multipeer manager: stop client ti,mer
2016-03-15 12:48:40.757 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:2
2016-03-15 12:48:40.758 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
,2016-03-15 12:48:40.770 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:2
,2016-03-15 12:48:40.774 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null

,ok 95 error should be null

,# setup

,2016-03-15 12:48:41.383 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:41.384 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:41.385 ThaliTest[1462:2354821] multipeer manager: stop client timer
,2016-03-15 12:48:41.385 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:48:41.388 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
2016-03-15 12:48:41.390 ThaliTest[1462:2354821] jxcore: stopListeningForAd,vertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 96 error should be null

,ok 97 error should be null

,# 26. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-15 12:48:41.829 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:41.829 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:41.830 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
,ok 98 error should be null

,ok 99 error should be null

,2016-03-15 12:48:41.836 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:41.836 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:41.837 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: suc,cess
ok 100 error should be null

,ok 101 error should be null

,# setup

,2016-03-15 12:48:42.140 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:42.141 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
,2016-03-15 12:48:42.141 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:42.144 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:42.146 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,ok 102 error should be null

,ok 103 error should be null

,# 27. #start should fail if called twice in a row

,# teardown

,ok 104 first call should succeed

,ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,2016-03-15 12:48:50.102 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
,2016-03-15 12:48:50.103 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
,2016-03-15 12:48:50.105 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:50.107 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:48:50.109 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-15 12:48:50.406 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
2016-03-15 12:48:50.407 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
2016-03-15 12:48:50.408 ThaliTest[1462:2354821] jxcore: star,tListeningForAdvertisements: success
,2016-03-15 12:48:50.437 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:48:50.439 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:3
,2016-03-15 12:48:50.441 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:3
,2016-03-15 12:48:50.445 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 called only once
,
,ok 110 discovery state matches

,ok 111 advertising state matches

,# setup

,2016-03-15 12:48:50.554 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:48:50.555 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:48:50.555 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
,2016-03-15 12:48:50.558 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
2016-03-15 12:48:50.559 ThaliTest[1462:2354821] multipeer manager: stop client timer
2016-03-15 12:48:50.560 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisem,ents: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 112 error should be null

,ok 113 error should be null

,# 29. does not send duplicate availability changes

,# teardown

,ok 114 should be called once

,ok 115 should not have been called more than once

,# setup

,ok 116 error should be null

,ok 117 error should be null

,# 30. can get the network status

,# teardown

,ok 118 network status should have certain non-empty properties
,
,# setup

,ok 119 error should be null

,ok 120 error should be null

,# 31. wifi peer is marked unavailable if announcements stop

,# teardown

,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined

,ok 121 host address should match

,ok 122 port should match

,ok 123 host address should be null

,ok 124 port should should be null

,# setup

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 125 error should be null

,ok 126 error should be null

,# 32. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-15 12:49:00.876 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
2016-03-15 12:49:00.877 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
2016-03-15 12:49:00.879 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements: success
,ok 127 Can call startListeningForAdvertisements without error

2016-03-15 12:49:00.884 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:00.887 ThaliTest[1462:2354821] multipeer manager: stop client timer
,2016-03-15 12:49:00.890 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
ok 128 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-15 12:49:01.177 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:01.177 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:01.177 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 12:49:01.178 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:01.179 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-15 12:49:01.529 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
2016-03-15 12:49:01.530 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
,2016-03-15 12:49:01.532 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error

2016-03-15 12:49:01.537 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
2016-03-15 12:49:01.538 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements: success
ok 1,30 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-15 12:49:01.771 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:01.772 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:01.772 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 12:49:01.773 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:01.773 ThaliTest[1462:2354821] multipeer manager: stop client timer
2016-03-15 12:49:01.777 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-15 12:49:02.383 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:49:02.384 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:4
2016-03-15 12:49:02.384 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
,2016-03-15 12:49:02.385 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:4
2016-03-15 12:49:02.386 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening: success
,ok 131 Can call startUpdateAdvertisingAndListening without error

2016-03-15 12:49:02.389 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:02.389 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:02.,389 ThaliTest[1462:2354821] multipeer manager: stop client timer
2016-03-15 12:49:02.390 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
ok 132 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-15 12:49:03.048 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:03.049 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:03.049 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:49:03.050 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:03.051 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-15 12:49:03.388 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:49:03.388 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:5
2016-03-15 12:49:03.389 ThaliTest[1462:2354821] multipeer m,anager: start client restart timer: 0x17ee7c00
2016-03-15 12:49:03.390 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:5
2016-03-15 12:49:03.390 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 133 Can call startUpdateAdvertisingAndListening without error

2016-03-15 12:49:03.394 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:49:03.395 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
,2016-03-15 12:49:03.395 ThaliTest[1462:2354821] multipeer manager: stop client timer
,2016-03-15 12:49:03.397 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:6
2016-03-15 12:49:03.398 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
2016-03-15 12:49:03.398 ThaliTest[1462:23548,21] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:6
2016-03-15 12:49:03.398 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening: success
ok 134 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-15 12:49:03.645 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:03.645 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:03.646 ThaliTest[1462:2354821] multipeer manager: stop client timer
20,16-03-15 12:49:03.646 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:49:03.647 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:03.651 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-15 12:49:03.864 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:49:03.864 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:7
2016-03-15 12:49:03.865 ThaliTest[1462:2354821] multipeer m,anager: start client restart timer: 0x17ee7c00
2016-03-15 12:49:03.866 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:7
2016-03-15 12:49:03.866 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 135 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-15 12:49:03.868 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
2016-03-15 12:49:03.870 ThaliTest[1462:2354821] jxcore: startListeningForAdvertise,ments: success
ok 136 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:05.001 ThaliTest[1462:2354620] client: found new peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:7
,ok 137 peer must have peerIdentifier

,ok 138 peerIdentifier must be a string

,# setup

,2016-03-15 12:49:05.742 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:05.742 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:05.743 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 12:49:05.743 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
2016-03-15 12:49:05.744 ThaliTest[1462:2354821] multipeer manager: stop client timer
,2016-03-15 12:49:05.748 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,# 37. Can connect to a remote peer

,# teardown

,2016-03-15 12:49:06.449 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
2016-03-15 12:49:06.450 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
2016-03-15 12:49:06.450 ThaliTest[1462:2354821] multipeer m,anager: start client restart timer: 0x17ee7c00
2016-03-15 12:49:06.451 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:8
2016-03-15 12:49:06.451 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 139 Can call startUpdateAdvertisingAndListening without error

2016-03-15 12:49:06.453 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
2016-03-15 12:49:06.454 ThaliTest[1462:2354821] jxcore: startListeningForAdvertis,ements: success
,ok 140 Can call startListeningForAdvertisements without error

,2016-03-15 12:49:07.514 ThaliTest[1462:2354620] client: found new peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:7
,2016-03-15 12:49:07.537 ThaliTest[1462:2354821] jxcore: connect D00D3980-DA15-4582-8F26-46DE57DE4C09:7
2016-03-15 12:49:07.538 ThaliTest[1462:2354821] client: server will connect
2016-03-15 12:49:07.538 ThaliTest[1462:2354821] client session: reverseConn,ect
2016-03-15 12:49:07.538 ThaliTest[1462:2354821] client session: stateChange:0->1 D00D3980-DA15-4582-8F26-46DE57DE4C09:7
,2016-03-15 12:49:07.805 ThaliTest[1462:2356053] client session: not connected D00D3980-DA15-4582-8F26-46DE57DE4C09:7
2016-03-15 12:49:07.807 ThaliTest[1462:2356053] client session: onLinkFailure: D00D3980-DA15-4582-8F26-46DE57DE4C09
2016-03-15 12:49:07.8,07 ThaliTest[1462:2356053] client session: disconnect
2016-03-15 12:49:07.807 ThaliTest[1462:2356053] client session: stateChange:1->0 D00D3980-DA15-4582-8F26-46DE57DE4C09:7
,2016-03-15 12:49:07.811 ThaliTest[1462:2356053] client session: no connect callback (server initiated)
,2016-03-15 12:49:08.808 ThaliTest[1462:2354620] multipeer session: reset timer
2016-03-15 12:49:08.809 ThaliTest[1462:2354620] server session: connect
2016-03-15 12:49:08.809 ThaliTest[1462:2354620] server session: stateChange:0->1 D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:08.819 ThaliTest[1462:2354620] server: accepting invitation D00D3980-DA15-4582-8F26-46DE57DE4C09
,2016-03-15 12:49:11.479 ThaliTest[1462:2356053] server session: connected
2016-03-15 12:49:11.479 ThaliTest[1462:2356053] server session: stateChange:1->2 D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:11.533 ThaliTest[1462:2354620] server relay: connected (to port: 61820)
2016-03-15 12:49:11.534 ThaliTest[1462:2354620] jxcore: connect: success
,{ clientPort: 61824, serverPort: 61820, listeningPort: 0 }

ok 141 Must have listeningPort

ok 142 listeningPort must be a number

ok 143 Connection must have clientPort

ok 144 clientPort must be a number

,ok 145 Connection must have serverPort

ok 146 serverPort must be a number

,ok 147 (unnamed assert)

,ok 148 (unnamed assert)

,# setup

,2016-03-15 12:49:11.871 ThaliTest[1462:2356030] server session: not connected D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:12.209 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening
2016-03-15 12:49:12.210 ThaliTest[1462:2354821] THEMultipeerManager stopping peer
2016-03-15 12:49:12.210 ThaliTest[1462:2354821] server session: disconnect
2016-03-15 1,2:49:12.210 ThaliTest[1462:2354821] server session: stateChange:2->0 D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:12.222 ThaliTest[1462:2354821] jxcore: stopAdvertisingAndListening: success
2016-03-15 12:49:12.224 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements
,2016-03-15 12:49:12.224 ThaliTest[1462:2354821] multipeer manager: stop client timer
2016-03-15 12:49:12.239 ThaliTest[1462:2354821] jxcore: stopListeningForAdvertisements: success
,# 38. Can shift large amounts of data

,# teardown

,2016-03-15 12:49:13.354 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 12:49:13.356 ThaliTest[1462:2354821] server: starting 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:49:13.359 ThaliTest[1462:2354821] multipeer manager: start client restart timer: 0x17ee7c00
,2016-03-15 12:49:13.362 ThaliTest[1462:2354821] THEMultipeerManager initialized peer 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-15 12:49:13.364 ThaliTest[1462:2354821] jxcore: startUpdateAdvertisingAndListening: success
,ok 149 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 12:49:13.368 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements
,2016-03-15 12:49:13.371 ThaliTest[1462:2354821] jxcore: startListeningForAdvertisements: success
,ok 150 Can call startListeningForAdvertisements without error
,
,2016-03-15 12:49:13.462 ThaliTest[1462:2354620] client: found new peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:13.485 ThaliTest[1462:2354821] jxcore: connect D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:13.487 ThaliTest[1462:2354821] client: server will connect
,2016-03-15 12:49:13.489 ThaliTest[1462:2354821] client session: reverseConnect
,2016-03-15 12:49:13.490 ThaliTest[1462:2354821] client session: stateChange:0->1 D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:14.443 ThaliTest[1462:2356054] client session: not connected D00D3980-DA15-4582-8F26-46DE57DE4C09:8
2016-03-15 12:49:14.443 ThaliTest[1462:2356054] client session: onLinkFailure: D00D3980-DA15-4582-8F26-46DE57DE4C09
2016-03-15 12:49:14.4,43 ThaliTest[1462:2356054] client session: disconnect
,2016-03-15 12:49:14.444 ThaliTest[1462:2356054] client session: stateChange:1->0 D00D3980-DA15-4582-8F26-46DE57DE4C09:8
,2016-03-15 12:49:14.447 ThaliTest[1462:2356054] client session: no connect callback (server initiated)
,2016-03-15 12:49:15.636 ThaliTest[1462:2354620] multipeer session: reset timer
2016-03-15 12:49:15.637 ThaliTest[1462:2354620] server: rejecting invitation from D00D3980-DA15-4582-8F26-46DE57DE4C09 due to previous generation (269C88B3-FCD7-4B25-9CB6-15E21,901468C:9 != 269C88B3-FCD7-4B25-9CB6-15E21901468C:8)
,2016-03-15 12:49:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:49:33.389 ThaliTest[1462:2354620] client: found updated peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:49:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:49:53.384 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:50:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:50:13.389 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:50:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:50:33.389 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:50:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:50:53.391 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:51:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:51:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:51:33.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:51:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:51:53.380 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:52:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:52:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:52:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:52:33.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:52:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:52:53.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:53:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:53:13.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:53:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:53:33.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:53:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:53:53.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:54:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:54:13.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:54:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:54:33.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:54:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:55:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:55:13.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:55:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:55:33.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:55:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:55:53.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:56:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:56:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:56:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:56:33.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:56:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:56:53.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:57:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:57:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:57:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:57:33.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:57:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:57:53.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:58:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:58:13.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:58:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:58:33.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:58:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:58:53.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:59:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:59:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:59:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:59:33.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 12:59:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 12:59:53.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:00:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:00:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:00:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:00:33.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:00:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:00:53.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:01:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:01:13.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:01:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:01:33.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:01:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:01:53.376 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:02:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:02:13.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:02:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:02:33.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:02:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:02:53.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:03:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:03:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:03:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:03:33.378 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:03:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:03:53.380 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:04:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:04:13.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:04:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:04:33.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:04:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:04:53.379 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:05:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:05:13.376 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:05:33.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:05:33.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:05:53.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:05:53.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9
,2016-03-15 13:06:13.363 ThaliTest[1462:2354620] multipeer manager: restart client
,2016-03-15 13:06:13.377 ThaliTest[1462:2354620] client: found existing peer: D00D3980-DA15-4582-8F26-46DE57DE4C09:9

```
