#### Test 62509094b685d58_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CF90E7BD-51B9-45FC-A084-EBCD0ABD5AE0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CF90E7BD-51B9-45FC-A084-EBCD0ABD5AE0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51995"
,(lldb)     command script import "/tmp/CF90E7BD-51B9-45FC-A084-EBCD0ABD5AE0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 12:27:51.539 ThaliTest[1689:2657787] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E253C7CA-849D-4837-B950-DE21E23E9C04/Library/Cookies/Cookies.binarycookies
,2016-03-17 12:27:51.946 ThaliTest[1689:2657787] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 12:27:51.948 ThaliTest[1689:2657787] Multi-tasking -> Device: YES, App: YES
,2016-03-17 12:27:51.966 ThaliTest[1689:2657787] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 12:27:53.835 ThaliTest[1689:2657787] Using UIWebView
,2016-03-17 12:27:53.844 ThaliTest[1689:2657787] [CDVTimer][handleopenurl] 0.495017ms
,2016-03-17 12:27:53.851 ThaliTest[1689:2657787] [CDVTimer][intentandnavigationfilter] 6.718993ms
,2016-03-17 12:27:53.852 ThaliTest[1689:2657787] [CDVTimer][gesturehandler] 0.314951ms
,2016-03-17 12:27:53.852 ThaliTest[1689:2657787] [CDVTimer][TotalPluginStartup] 9.106040ms
,2016-03-17 12:28:00.544 ThaliTest[1689:2657787] Resetting plugins due to page load.
,2016-03-17 12:28:03.507 ThaliTest[1689:2657787] Finished load of: file:///var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/index.html
,2016-03-17 12:28:03.715 ThaliTest[1689:2657787] JXcore Cordova plugin initializing
,2016-03-17 12:28:03.716 ThaliTest[1689:2658009] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 12:28:07.495 ThaliTest[1689:2658009] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-17 12:28:07.496 ThaliTest[1689:2658009] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-17 12:28:07.496 ThaliTest[1689:2658009] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 12:28:07.498 ThaliTest[1689:2658009] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3CD13841-7BE3-4224-9743-806A1A437533/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 12:28:15.281 ThaliTest[1689:2657787] THREAD WARNING: ['JXcore'] took '5592.681152' ms. Plugin should use a background thread.
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
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,# 4. native server connections all up
,# teardown
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# setup
,# 5. native server - closing incoming stream cleans outgoing socket
,# teardown
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,# 6. native server - closing incoming connection cleans outgoing socket
,# teardown
,ok 14 we should not have gotten an error
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,# 8. native server - closing the whole server cleans everything up
,# teardown
,ok 20 we should not have gotten an error
,ok 21 Buffers are identical
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,ok 31 we should not have gotten an error
,ok 32 Buffers are identical
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,ok 38 we should not have gotten an error
,ok 39 Buffers are identical
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
,ok 82 error should be null
,ok 83 error should be null
,ok 84 error should be null
,ok 85 error should be null
,# setup
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,ok 88 error should be null
,ok 89 error should be null
,ok 90 error should be null
,ok 91 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,ok 94 error should be null
,ok 95 error should be null
,ok 96 error should be null
,ok 97 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,ok 100 error should be null
,ok 101 error should be null
,ok 102 error should be null
,ok 103 error should be null
,# setup
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
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
,ok 123 host address should match
,ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-17 12:31:30.350 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements
,2016-03-17 12:31:30.351 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 12:31:30.354 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:30.361 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements
,2016-03-17 12:31:30.362 ThaliTest[1689:2658009] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-03-17 12:31:30.365 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-17 12:31:30.642 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 12:31:30.645 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:30.648 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening
,2016-03-17 12:31:30.648 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
,2016-03-17 12:31:30.648 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 12:31:31.129 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements
,2016-03-17 12:31:31.130 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 12:31:31.132 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:31.136 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 12:31:31.139 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 12:31:31.642 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements
,2016-03-17 12:31:31.642 ThaliTest[1689:2658009] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 12:31:31.645 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:31.649 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening
,2016-03-17 12:31:31.650 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
,2016-03-17 12:31:31.650 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 12:31:32.881 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening
,2016-03-17 12:31:32.882 ThaliTest[1689:2658009] server: starting 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:1
,2016-03-17 12:31:32.883 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
,2016-03-17 12:31:32.884 ThaliTest[1689:2658009] THEMultipeerManager initialized peer 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:1
,2016-03-17 12:31:32.885 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 12:31:32.888 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening
2016-03-17 12:31:32.889 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
2016-03-17 12:31:32.889 ThaliTest[1689:2658009] multipeer manager: stop client timer
20,16-03-17 12:31:32.890 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-17 12:31:33.183 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 12:31:33.185 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:33.188 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening
,2016-03-17 12:31:33.188 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
2016-03-17 12:31:33.189 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening: success
,ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 12:31:33.413 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening
,2016-03-17 12:31:33.414 ThaliTest[1689:2658009] server: starting 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:2
,2016-03-17 12:31:33.415 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
2016-03-17 12:31:33.416 ThaliTest[1689:2658009] THEMultipeerManager initialized peer 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:2
2016-03-17 12:31:33.416 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening: success
,ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 12:31:33.419 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening
,2016-03-17 12:31:33.419 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
2016-03-17 12:31:33.420 ThaliTest[1689:2658009] multipeer manager: stop client timer
2016-03-17 12:31:33.421 ThaliTest[1689:2658009] server: starting 32B08C85-F042-4FA8-ADF,8-9E6C0A7C58B7:3
2016-03-17 12:31:33.421 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
2016-03-17 12:31:33.422 ThaliTest[1689:2658009] THEMultipeerManager initialized peer 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:3
2016-0,3-17 12:31:33.422 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-17 12:31:34.953 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 12:31:34.956 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:34.958 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening
,2016-03-17 12:31:34.959 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
,2016-03-17 12:31:34.959 ThaliTest[1689:2658009] multipeer manager: stop client timer
,2016-03-17 12:31:34.960 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening: success
,ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 12:31:35.411 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening
,2016-03-17 12:31:35.411 ThaliTest[1689:2658009] server: starting 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
,2016-03-17 12:31:35.412 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
2016-03-17 12:31:35.413 ThaliTest[1689:2658009] THEMultipeerManager initialized peer 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:35.413 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening: success
,ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-17 12:31:35.418 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 12:31:35.420 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:36.491 ThaliTest[1689:2657787] client: found new peer: 073917DB-1D47-40B2-A8E8-69D166708C51:4
,ok 147 peers must be an array
,ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 12:31:37.707 ThaliTest[1689:2657787] client: found new peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:31:38.628 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 12:31:38.630 ThaliTest[1689:2658009] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:38.632 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening
,2016-03-17 12:31:38.633 ThaliTest[1689:2658009] THEMultipeerManager stopping peer
,2016-03-17 12:31:38.634 ThaliTest[1689:2658009] multipeer manager: stop client timer
,2016-03-17 12:31:38.634 ThaliTest[1689:2658009] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 12:31:38.995 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening
2016-03-17 12:31:38.996 ThaliTest[1689:2658009] server: starting 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:31:38.997 ThaliTest[1689:2658009] multipeer manager: start client restart timer: 0x14f7a650
2016-03-17 12:31:38.998 ThaliTest[1689:2658009] THEMultipeerManager initialized peer 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:31:38.998 ThaliTest[1689:2658009] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 12:31:39.001 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 12:31:39.003 ThaliTest[1689:2658009] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:39.835 ThaliTest[1689:2657787] client: found new peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"269C88B3-FCD7-4B25-9CB6-15E21901468C:9","pleaseConnect":0}]
,2016-03-17 12:31:39.840 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:31:39.841 ThaliTest[1689:2658009] client session: connect
2016-03-17 12:31:39.841 ThaliTest[1689:2658009] client session: stateChange:0->1 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:31:39.869 ThaliTest[1689:2657787] client: found new peer: 073917DB-1D47-40B2-A8E8-69D166708C51:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"073917DB-1D47-40B2-A8E8-69D166708C51:4","pleaseConnect":0}]
,2016-03-17 12:31:41.610 ThaliTest[1689:2657787] multipeer session: reset timer
,2016-03-17 12:31:41.611 ThaliTest[1689:2657787] server: rejecting invitation from 073917DB-1D47-40B2-A8E8-69D166708C51 due to previous generation (32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5 != 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4)
,2016-03-17 12:31:53.532 ThaliTest[1689:2657787] multipeer session: reset timer
,2016-03-17 12:31:53.532 ThaliTest[1689:2657787] server: disconnecting to refresh session (073917DB-1D47-40B2-A8E8-69D166708C51)
2016-03-17 12:31:53.533 ThaliTest[1689:2657787] server: rejecting invitation from 073917DB-1D47-40B2-A8E8-69D166708C51 due to previous generation (32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5 != 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4)
,2016-03-17 12:31:58.686 ThaliTest[1689:2657787] client: lost peer: 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:31:58.686 ThaliTest[1689:2657787] client session: onPeerLost: 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:31:58.686 ThaliTest[1689:2657787] client session: onLinkFailure: 269C88B3-FCD7-4B25-9CB6-15E21901468C
2016-03-17 12:31:58.687 ThaliTest[1689:2657787] client session: disconnect
,2016-03-17 12:31:58.687 ThaliTest[1689:2657787] client session: stateChange:1->0 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:31:58.688 ThaliTest[1689:2657787] client session: fireConnectCallback: 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:31:58.688 ThaliTest[1689:2657787] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-17 12:31:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:31:59.013 ThaliTest[1689:2657787] client: found updated peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"073917DB-1D47-40B2-A8E8-69D166708C51:5","pleaseConnect":0}]
,2016-03-17 12:32:01.698 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:01.699 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:01.699 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-17 12:32:04.722 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
2016-03-17 12:32:04.723 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:04.723 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-17 12:32:06.785 ThaliTest[1689:2657787] multipeer session: reset timer
2016-03-17 12:32:06.785 ThaliTest[1689:2657787] server: disconnecting to refresh session (073917DB-1D47-40B2-A8E8-69D166708C51)
,2016-03-17 12:32:06.785 ThaliTest[1689:2657787] server: rejecting invitation from 073917DB-1D47-40B2-A8E8-69D166708C51 due to previous generation (32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5 != 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4)
,2016-03-17 12:32:07.744 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:07.745 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
2016-03-17 12:32:07.746 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-17 12:32:10.758 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:10.759 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:10.760 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-17 12:32:13.773 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:13.773 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:13.774 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-17 12:32:16.790 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
2016-03-17 12:32:16.791 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
2016-03-17 12:32:16.791 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-17 12:32:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:32:19.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:32:19.228 ThaliTest[1689:2657787] multipeer session: reset timer
,2016-03-17 12:32:19.229 ThaliTest[1689:2657787] server: disconnecting to refresh session (073917DB-1D47-40B2-A8E8-69D166708C51)
,2016-03-17 12:32:19.229 ThaliTest[1689:2657787] server: rejecting invitation from 073917DB-1D47-40B2-A8E8-69D166708C51 due to previous generation (32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5 != 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4)
,2016-03-17 12:32:19.812 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:19.813 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:19.814 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-17 12:32:22.835 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:22.836 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:22.837 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-17 12:32:25.849 ThaliTest[1689:2658009] jxcore: connect 269C88B3-FCD7-4B25-9CB6-15E21901468C:9
,2016-03-17 12:32:25.850 ThaliTest[1689:2658009] client: connect: unreachable 269C88B3-FCD7-4B25-9CB6-15E21901468C
,2016-03-17 12:32:25.851 ThaliTest[1689:2658009] jxcore: connect: fail: Peer unreachable
,INFO testThaliMobileNative Connect returned an error: Peer unreachable
,WARN testThaliMobileNative Too many connect retries!
,2016-03-17 12:32:32.850 ThaliTest[1689:2657787] multipeer session: reset timer
2016-03-17 12:32:32.851 ThaliTest[1689:2657787] server: disconnecting to refresh session (073917DB-1D47-40B2-A8E8-69D166708C51)
,2016-03-17 12:32:32.851 ThaliTest[1689:2657787] server: rejecting invitation from 073917DB-1D47-40B2-A8E8-69D166708C51 due to previous generation (32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5 != 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4)
,2016-03-17 12:32:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:32:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:32:45.424 ThaliTest[1689:2657787] multipeer session: reset timer
2016-03-17 12:32:45.424 ThaliTest[1689:2657787] server: disconnecting to refresh session (073917DB-1D47-40B2-A8E8-69D166708C51)
2016-03-17 12:32:45.425 ThaliTest[1689:2657787] server: rejecting invitation from 073917DB-1D47-40B2-A8E8-69D166708C51 due to previous generation (32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5 != 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4)
,2016-03-17 12:32:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:32:59.015 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:33:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:33:19.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:33:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:33:39.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:33:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:33:59.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:34:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:34:19.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:34:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:34:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:34:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:34:59.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:35:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:35:19.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:35:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:35:39.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:35:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:35:59.015 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:36:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:36:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:36:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:36:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:36:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:36:59.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:37:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:37:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:37:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:37:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:37:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:37:59.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:38:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:38:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:38:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:38:39.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:38:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:38:59.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:39:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:39:19.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:39:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:39:39.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:39:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:39:59.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:40:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:40:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:40:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:40:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:40:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:40:59.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:41:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:41:19.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:41:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:41:39.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:41:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:41:59.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:42:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:42:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:42:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:42:39.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:42:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:42:59.011 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:43:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:43:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:43:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:43:39.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:43:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:43:59.011 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:44:18.998 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:44:19.011 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:44:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:44:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:44:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:44:59.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:45:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:45:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:45:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:45:39.015 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:45:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:45:59.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:46:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:46:19.011 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:46:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:46:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:46:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:46:59.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:47:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:47:19.013 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:47:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:47:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:47:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:47:59.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:48:18.998 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:48:19.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:48:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:48:39.012 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:48:58.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:48:59.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:49:18.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:49:19.011 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5
,2016-03-17 12:49:38.999 ThaliTest[1689:2657787] multipeer manager: restart client
,2016-03-17 12:49:39.014 ThaliTest[1689:2657787] client: found existing peer: 073917DB-1D47-40B2-A8E8-69D166708C51:5

```
