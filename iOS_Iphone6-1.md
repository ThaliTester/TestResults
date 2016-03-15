#### Test 625481247d7767b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/85037DAE-D2E1-4A15-B105-23C19DFC7B42/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/85037DAE-D2E1-4A15-B105-23C19DFC7B42/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49705"
,(lldb)     command script import "/tmp/85037DAE-D2E1-4A15-B105-23C19DFC7B42/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 15:00:47.406 ThaliTest[1440:2308073] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/67350DF7-8543-4693-A1BE-44B847F9A30E/Library/Cookies/Cookies.binarycookies
,2016-03-15 15:00:47.809 ThaliTest[1440:2308073] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 15:00:47.811 ThaliTest[1440:2308073] Multi-tasking -> Device: YES, App: YES
,2016-03-15 15:00:47.838 ThaliTest[1440:2308073] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 15:00:49.827 ThaliTest[1440:2308073] Using UIWebView
,2016-03-15 15:00:49.834 ThaliTest[1440:2308073] [CDVTimer][handleopenurl] 0.598013ms
,2016-03-15 15:00:49.842 ThaliTest[1440:2308073] [CDVTimer][intentandnavigationfilter] 7.197022ms
2016-03-15 15:00:49.843 ThaliTest[1440:2308073] [CDVTimer][gesturehandler] 0.353992ms
2016-03-15 15:00:49.843 ThaliTest[1440:2308073] [CDVTimer][TotalPluginS,tartup] 9.831011ms
,2016-03-15 15:00:56.700 ThaliTest[1440:2308073] Resetting plugins due to page load.
,2016-03-15 15:01:00.220 ThaliTest[1440:2308073] Finished load of: file:///var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/index.html
,2016-03-15 15:01:00.382 ThaliTest[1440:2308073] JXcore Cordova plugin initializing
,2016-03-15 15:01:00.383 ThaliTest[1440:2308306] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 15:01:14.459 ThaliTest[1440:2308306] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 15:01:14.460 ThaliTest[1440:2308306] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 15:01:14.460 ThaliTest[1440:2308306] jxcore: didRegisterToNative networkChanged
,2016-03-15 15:01:14.461 ThaliTest[1440:2308306] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3AB4EBAE-629E-40CC-9091-C0A950D5B84E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

ok 27 native server should be closed

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

,2016-03-15 15:04:25.767 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:25.768 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,ok 80 error should be null

,ok 81 error should be null

,2016-03-15 15:04:25.774 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:25.776 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null

,ok 83 error should be null

,# setup

,2016-03-15 15:04:26.032 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:26.032 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:26.032 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:26.034 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:26.036 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null

,ok 85 error should be null

,# 24. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-15 15:04:26.332 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
2016-03-15 15:04:26.333 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
,2016-03-15 15:04:26.336 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements: success
,ok 86 error should be null

ok 87 error should be null

,2016-03-15 15:04:26.351 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
2016-03-15 15:04:26.352 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null

,ok 89 error should be null

,# setup

,2016-03-15 15:04:26.591 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:26.592 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:26.592 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
2016-03-15 15:04:26.592 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:26.593 ThaliTest[1440:2308306] multipeer manager: stop client timer
,2016-03-15 15:04:26.596 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 90 error should be null

,ok 91 error should be null

,# 25. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-15 15:04:27.207 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:27.209 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:1
,2016-03-15 15:04:27.210 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
,2016-03-15 15:04:27.213 ThaliTest[1440:2308306] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:1
2016-03-15 15:04:27.214 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening: success
,ok 92 error should be null

,ok 93 error should be null

,2016-03-15 15:04:27.241 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:27.243 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:27.243 ThaliTest[1440:2308306] multipeer manager: stop client timer
2016-03-15 15:04:27.244 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED,7-4D439DFED9FC:2
2016-03-15 15:04:27.244 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
2016-03-15 15:04:27.245 ThaliTest[1440:2308306] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:2
2016-0,3-15 15:04:27.245 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null

,ok 95 error should be null

,# setup

,2016-03-15 15:04:27.822 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:27.823 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:27.823 ThaliTest[1440:2308306] multipeer manager: stop client timer
20,16-03-15 15:04:27.824 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:27.826 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:27.827 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 96 error should be null

,ok 97 error should be null

,# 26. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-15 15:04:28.829 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:28.830 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:28.831 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
,ok 98 error should be null

,ok 99 error should be null

,2016-03-15 15:04:28.836 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:28.837 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:28.837 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
ok 100 error should be null

,ok 101 error should be null

,# setup

,2016-03-15 15:04:29.211 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:29.212 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:29.212 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 15:04:29.213 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:29.214 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,ok 102 error should be null

,ok 103 error should be null

,# 27. #start should fail if called twice in a row

,# teardown

,ok 104 first call should succeed

,ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,2016-03-15 15:04:29.959 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:29.960 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:29.960 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
2016-03-15 15:04:29.961 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:29.962 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-15 15:04:30.443 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:30.444 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
2016-03-15 15:04:30.446 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements: success
,2016-03-15 15:04:30.461 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:30.461 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:3
2016-03-15 15:04:30.462 ThaliTest[1440:2308306] THEMultipee,rManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:3
2016-03-15 15:04:30.462 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 called only once

ok 110 discovery state matches

,ok 111 advertising state matches

,# setup

,2016-03-15 15:04:30.799 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:30.799 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:30.800 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
2016-03-15 15:04:30.801 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:30.801 ThaliTest[1440:2308306] multipeer manager: stop client timer
2016-03-15 15:04:30.805 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

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

,2016-03-15 15:04:37.096 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
2016-03-15 15:04:37.097 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
2016-03-15 15:04:37.098 ThaliTest[1440:2308306] jxcore: star,tListeningForAdvertisements: success
ok 127 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:37.100 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:37.101 ThaliTest[1440:2308306] multipeer manager: stop client timer
,2016-03-15 15:04:37.103 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,ok 128 Can call stopListeningForAdvertisements without error

# setup

,2016-03-15 15:04:37.873 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:37.874 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:37.874 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 15:04:37.875 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:37.875 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-15 15:04:38.920 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
2016-03-15 15:04:38.921 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
2016-03-15 15:04:38.922 ThaliTest[1440:2308306] jxcore: star,tListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:38.924 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:38.926 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements: success
ok 130 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-15 15:04:39.439 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:39.440 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:39.440 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 15:04:39.441 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:39.441 ThaliTest[1440:2308306] multipeer manager: stop client timer
2016-03-15 15:04:39.442 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-15 15:04:39.968 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:39.969 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:4
2016-03-15 15:04:39.970 ThaliTest[1440:2308306] multipeer m,anager: start client restart timer: 0x146dd530
2016-03-15 15:04:39.970 ThaliTest[1440:2308306] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:4
2016-03-15 15:04:39.971 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 131 Can call startUpdateAdvertisingAndListening without error

2016-03-15 15:04:39.972 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:39.973 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
,2016-03-15 15:04:39.974 ThaliTest[1440:2308306] multipeer manager: stop client timer
,2016-03-15 15:04:39.975 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
,ok 132 Can call stopAdvertisingAndListening without error

# setup

,2016-03-15 15:04:40.257 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:40.258 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:40.258 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 15:04:40.259 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:40.260 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-15 15:04:40.884 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:40.885 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:5
2016-03-15 15:04:40.886 ThaliTest[1440:2308306] multipeer m,anager: start client restart timer: 0x146dd530
2016-03-15 15:04:40.886 ThaliTest[1440:2308306] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:5
2016-03-15 15:04:40.887 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 133 Can call startUpdateAdvertisingAndListening without error

2016-03-15 15:04:40.888 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:40.890 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:40.890 ThaliTest[1440:2308306] multipeer manager: stop client timer
,2016-03-15 15:04:40.892 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:6
2016-03-15 15:04:40.892 ThaliTest[1440:2308306] multipeer manager: start client restart timer: 0x146dd530
2016-03-15 15:04:40.893 ThaliTest[1440:23083,06] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:6
2016-03-15 15:04:40.893 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening: success
ok 134 Can call startUpdateAdvertisingAndListening twice without error

,# setup
,
,2016-03-15 15:04:41.193 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:41.194 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:41.194 ThaliTest[1440:2308306] multipeer manager: stop client timer
20,16-03-15 15:04:41.194 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: success
2016-03-15 15:04:41.195 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:41.196 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements: success
,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-15 15:04:42.913 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:42.914 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
2016-03-15 15:04:42.914 ThaliTest[1440:2308306] multipeer m,anager: start client restart timer: 0x146dd530
2016-03-15 15:04:42.915 ThaliTest[1440:2308306] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
2016-03-15 15:04:42.915 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 135 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-15 15:04:42.917 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:42.920 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements: success
ok 136 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:44.864 ThaliTest[1440:2308073] client: found new peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
,ok 137 peer must have peerIdentifier

,ok 138 peerIdentifier must be a string

,# setup

,2016-03-15 15:04:44.985 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:44.986 ThaliTest[1440:2308306] THEMultipeerManager stopping peer
2016-03-15 15:04:44.986 ThaliTest[1440:2308306] jxcore: stopAdvertisingAndListening: suc,cess
2016-03-15 15:04:44.987 ThaliTest[1440:2308306] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:44.987 ThaliTest[1440:2308306] multipeer manager: stop client timer
2016-03-15 15:04:44.988 ThaliTest[1440:2308306] jxcore: stopListeningForAdve,rtisements: success
,# 37. Can connect to a remote peer

,# teardown

,2016-03-15 15:04:45.546 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:45.547 ThaliTest[1440:2308306] server: starting 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
2016-03-15 15:04:45.548 ThaliTest[1440:2308306] multipeer m,anager: start client restart timer: 0x146dd530
2016-03-15 15:04:45.548 ThaliTest[1440:2308306] THEMultipeerManager initialized peer 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
2016-03-15 15:04:45.548 ThaliTest[1440:2308306] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 139 Can call startUpdateAdvertisingAndListening without error

2016-03-15 15:04:45.551 ThaliTest[1440:2308306] jxcore: startListeningForAdvertisements
2016-03-15 15:04:45.551 ThaliTest[1440:2308306] jxcore: startListeningForAdvertis,ements: success
ok 140 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:46.513 ThaliTest[1440:2308073] client: found new peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
2016-03-15 15:04:46.531 ThaliTest[1440:2308306] jxcore: connect 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
2016-03-15 15:04:46.532 ThaliTest[1440:2,308306] client: server will connect
2016-03-15 15:04:46.532 ThaliTest[1440:2308306] client session: reverseConnect
2016-03-15 15:04:46.533 ThaliTest[1440:2308306] client session: stateChange:0->1 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
,2016-03-15 15:04:46.607 ThaliTest[1440:2308073] multipeer session: reset timer
,2016-03-15 15:04:46.608 ThaliTest[1440:2308073] server: rejecting invitation from 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73 due to previous generation (0A147418-2D09-407B-8ED7-4D439DFED9FC:8 != 0A147418-2D09-407B-8ED7-4D439DFED9FC:7)
,2016-03-15 15:04:47.616 ThaliTest[1440:2308667] client session: not connected 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
2016-03-15 15:04:47.617 ThaliTest[1440:2308667] client session: onLinkFailure: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73
,2016-03-15 15:04:47.617 ThaliTest[1440:2308667] client session: disconnect
,2016-03-15 15:04:47.619 ThaliTest[1440:2308667] client session: stateChange:1->0 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
2016-03-15 15:04:47.620 ThaliTest[1440:2308667] client session: no connect callback (server initiated)
,2016-03-15 15:05:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:05:05.568 ThaliTest[1440:2308073] client: found updated peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:05:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:05:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:05:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:05:45.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:06:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:06:05.569 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:06:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:06:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:06:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:06:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:07:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:07:05.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:07:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:07:25.570 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:07:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:07:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:08:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:08:05.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:08:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:08:25.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:08:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:08:45.569 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:09:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:09:05.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:09:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:09:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:09:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:09:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:10:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:10:05.569 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:10:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:10:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:10:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:10:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:11:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:11:05.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:11:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:11:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:11:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:11:45.565 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:12:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:12:05.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:12:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:12:25.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:12:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:12:45.565 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:13:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:13:05.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:13:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:13:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:13:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:13:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:14:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:14:05.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:14:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:14:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:14:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:14:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:15:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:15:05.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:15:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:15:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:15:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:15:45.565 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:16:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:16:05.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:16:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:16:25.569 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:16:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:16:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:17:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:17:05.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:17:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:17:25.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:17:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:17:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:18:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:18:05.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:18:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:18:25.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:18:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:18:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:19:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:19:05.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:19:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:19:25.569 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:19:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:19:45.567 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:20:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:20:05.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:20:25.548 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:20:25.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:20:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:20:45.568 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:21:05.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:21:05.565 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:21:25.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:21:25.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:21:45.549 ThaliTest[1440:2308073] multipeer manager: restart client
,2016-03-15 15:21:45.566 ThaliTest[1440:2308073] client: found existing peer: 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8

```
