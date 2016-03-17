#### Test 625090941eef958_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625090941eef958/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7C27CAB3-7068-4DF4-87B1-1D1263195C9D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7C27CAB3-7068-4DF4-87B1-1D1263195C9D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625090941eef958/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625090941eef958/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51175"
,(lldb)     command script import "/tmp/7C27CAB3-7068-4DF4-87B1-1D1263195C9D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 08:33:16.906 ThaliTest[1591:2564215] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7514F9D3-3AD9-4D1E-B214-BDE6E8463F5F/Library/Cookies/Cookies.binarycookies
,2016-03-17 08:33:17.269 ThaliTest[1591:2564215] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 08:33:17.270 ThaliTest[1591:2564215] Multi-tasking -> Device: YES, App: YES
,2016-03-17 08:33:17.292 ThaliTest[1591:2564215] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 08:33:19.044 ThaliTest[1591:2564215] Using UIWebView
,2016-03-17 08:33:19.054 ThaliTest[1591:2564215] [CDVTimer][handleopenurl] 0.576019ms
,2016-03-17 08:33:19.061 ThaliTest[1591:2564215] [CDVTimer][intentandnavigationfilter] 7.291019ms
2016-03-17 08:33:19.062 ThaliTest[1591:2564215] [CDVTimer][gesturehandler] 0.349998ms
2016-03-17 08:33:19.063 ThaliTest[1591:2564215] [CDVTimer][TotalPluginS,tartup] 9.900987ms
,2016-03-17 08:33:25.934 ThaliTest[1591:2564215] Resetting plugins due to page load.
,2016-03-17 08:33:29.269 ThaliTest[1591:2564215] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/index.html
,2016-03-17 08:33:29.484 ThaliTest[1591:2564215] JXcore Cordova plugin initializing
,2016-03-17 08:33:29.486 ThaliTest[1591:2564400] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 08:33:33.696 ThaliTest[1591:2564400] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 08:33:33.697 ThaliTest[1591:2564400] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 08:33:33.697 ThaliTest[1591:2564400] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 08:33:33.700 ThaliTest[1591:2564400] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E446ACA-FDA2-4BFC-9F25-7EDA26600EB2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 08:33:42.414 ThaliTest[1591:2564215] THREAD WARNING: ['JXcore'] took '6248.354980' ms. Plugin should use a background thread.
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
,2016-03-17 08:40:05.745 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements
,2016-03-17 08:40:05.748 ThaliTest[1591:2564400] multipeer manager: start client restart timer: 0x14ee7e40
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 08:40:05.750 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:05.753 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
2016-03-17 08:40:05.754 ThaliTest[1591:2564400] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}
2016-03-17 08:40:05.761 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-17 08:40:06.068 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 08:40:06.070 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:06.073 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:06.074 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
2016-03-17 08:40:06.074 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 08:40:06.644 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements
2016-03-17 08:40:06.645 ThaliTest[1591:2564400] multipeer manager: start client restart timer: 0x14ee7e40
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 08:40:06.647 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-17 08:40:06.651 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discove,ryActive":true}
2016-03-17 08:40:06.653 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 08:40:07.067 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
2016-03-17 08:40:07.067 ThaliTest[1591:2564400] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 08:40:07.069 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 08:40:07.072 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:07.073 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
2016-03-17 08:4,0:07.073 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 08:40:07.274 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:07.275 ThaliTest[1591:2564400] server: starting B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:1
,2016-03-17 08:40:07.279 ThaliTest[1591:2564400] multipeer manager: start client restart timer: 0x14ee7e40
,2016-03-17 08:40:07.288 ThaliTest[1591:2564400] THEMultipeerManager initialized peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:1
,2016-03-17 08:40:07.289 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 08:40:07.293 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
,2016-03-17 08:40:07.295 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
,2016-03-17 08:40:07.300 ThaliTest[1591:2564400] multipeer manager: stop client timer
,2016-03-17 08:40:07.303 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-17 08:40:07.670 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 08:40:07.672 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:07.675 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
,2016-03-17 08:40:07.676 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
2016-03-17 08:40:07.677 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 08:40:08.255 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:08.255 ThaliTest[1591:2564400] server: starting B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:2
2016-03-17 08:40:08.256 ThaliTest[1591:2564400] multipeer m,anager: start client restart timer: 0x14ee7e40
2016-03-17 08:40:08.257 ThaliTest[1591:2564400] THEMultipeerManager initialized peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:2
2016-03-17 08:40:08.257 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:08.259 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:08.260 ThaliTest[1591:2564400] THEMultipeerManager stopping pee,r
2016-03-17 08:40:08.260 ThaliTest[1591:2564400] multipeer manager: stop client timer
2016-03-17 08:40:08.260 ThaliTest[1591:2564400] server: starting B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:3
2016-03-17 08:40:08.261 ThaliTest[1591:2564400] multipeer mana,ger: start client restart timer: 0x14ee7e40
,2016-03-17 08:40:08.267 ThaliTest[1591:2564400] THEMultipeerManager initialized peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:3
,2016-03-17 08:40:08.267 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-17 08:40:08.557 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 08:40:08.559 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:08.562 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:08.562 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
2016-03-17 08:40:08.563 ThaliTest[1591:2564400] multipeer manager: stop client timer
20,16-03-17 08:40:08.563 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 08:40:09.077 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:09.078 ThaliTest[1591:2564400] server: starting B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:09.079 ThaliTest[1591:2564400] multipeer m,anager: start client restart timer: 0x14ee7e40
2016-03-17 08:40:09.079 ThaliTest[1591:2564400] THEMultipeerManager initialized peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4
2016-03-17 08:40:09.080 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-17 08:40:09.085 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discov,eryActive":true}
2016-03-17 08:40:09.086 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:10.597 ThaliTest[1591:2564215] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
ok 147 peers must be an array
ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 08:40:10.937 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 08:40:10.939 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:10.943 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:10.943 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
2016-03-17 08:40:10.944 ThaliTest[1591:2564400] multipeer manager: stop client timer
20,16-03-17 08:40:10.944 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 08:40:11.696 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:11.697 ThaliTest[1591:2564400] server: starting B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:11.697 ThaliTest[1591:2564400] multipeer m,anager: start client restart timer: 0x14ee7e40
2016-03-17 08:40:11.698 ThaliTest[1591:2564400] THEMultipeerManager initialized peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5
2016-03-17 08:40:11.698 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:11.703 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 08:40:11.705 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:12.625 ThaliTest[1591:2564215] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,[ { peerAvailable: 1,
    peerIdentifier: 'B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4',
    pleaseConnect: 0 } ]
,2016-03-17 08:40:12.636 ThaliTest[1591:2564400] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
2016-03-17 08:40:12.637 ThaliTest[1591:2564400] client: server will connect
2016-03-17 08:40:12.637 ThaliTest[1591:2564400] client session: reverseConnect
2016-03-17 08:40:12.638 ThaliTest[1591:2564400] client session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,2016-03-17 08:40:12.794 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:12.795 ThaliTest[1591:2564215] server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D0,6013F6D:5 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:15.872 ThaliTest[1591:2565196] client session: not connected B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
2016-03-17 08:40:15.873 ThaliTest[1591:2565196] client session: onLinkFailure: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
,2016-03-17 08:40:15.874 ThaliTest[1591:2565196] client session: disconnect
,2016-03-17 08:40:15.875 ThaliTest[1591:2565196] client session: stateChange:1->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,2016-03-17 08:40:15.878 ThaliTest[1591:2565196] client session: no connect callback (server initiated)
,2016-03-17 08:40:15.888 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:15.888 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:15.889 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:19.354 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:19.355 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:19.355 ThaliTest[1591:2564215] server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:22.565 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:22.566 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:22.566 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:22.639 ThaliTest[1591:2564215] jxcore: connect: fail: Timed out awaiting reverse connection
,2016-03-17 08:40:25.652 ThaliTest[1591:2564400] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,2016-03-17 08:40:25.653 ThaliTest[1591:2564400] client: server will connect
2016-03-17 08:40:25.656 ThaliTest[1591:2564400] client session: reverseConnect
2016-03-17 08:40:25.656 ThaliTest[1591:2564400] client session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,2016-03-17 08:40:25.673 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:25.674 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:25.674 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:25.780 ThaliTest[1591:2565168] client session: not connected B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,2016-03-17 08:40:25.781 ThaliTest[1591:2565168] client session: onLinkFailure: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
,2016-03-17 08:40:25.782 ThaliTest[1591:2565168] client session: disconnect
,2016-03-17 08:40:25.783 ThaliTest[1591:2565168] client session: stateChange:1->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:4
,2016-03-17 08:40:25.784 ThaliTest[1591:2565168] client session: no connect callback (server initiated)
,2016-03-17 08:40:28.854 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:28.854 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:28.854 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:31.699 ThaliTest[1591:2564215] multipeer manager: restart client
,2016-03-17 08:40:31.718 ThaliTest[1591:2564215] client: found updated peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
[ { peerAvailable: 1,
    peerIdentifier: 'B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5',
    pleaseConnect: 0 } ]
,2016-03-17 08:40:31.722 ThaliTest[1591:2564400] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:31.723 ThaliTest[1591:2564400] client: server will connect
,2016-03-17 08:40:31.724 ThaliTest[1591:2564400] client session: reverseConnect
2016-03-17 08:40:31.725 ThaliTest[1591:2564400] client session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:31.969 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:31.970 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:31.970 ThaliTest[1591:2564215], server session: connect
2016-03-17 08:40:31.971 ThaliTest[1591:2564215] server session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:31.981 ThaliTest[1591:2564215] server: accepting invitation B834405C-4BB1-4DDE-BBBE-95797DDD18CB
,2016-03-17 08:40:32.003 ThaliTest[1591:2565304] client session: not connected B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:32.005 ThaliTest[1591:2565304] client session: onLinkFailure: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
,2016-03-17 08:40:32.008 ThaliTest[1591:2565304] client session: disconnect
,2016-03-17 08:40:32.009 ThaliTest[1591:2565304] client session: stateChange:1->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:32.012 ThaliTest[1591:2565304] client session: no connect callback (server initiated)
,2016-03-17 08:40:33.418 ThaliTest[1591:2565304] server session: p2p link connected
,2016-03-17 08:40:33.562 ThaliTest[1591:2564215] server relay: connected (to port: 63166)
2016-03-17 08:40:33.564 ThaliTest[1591:2564215] server session: stateChange:1->2 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:33.564 ThaliTest[1591:256421,5] jxcore: connect: success
{ clientPort: 63172, serverPort: 63166, listeningPort: 0 }
ok 157 Must have listeningPort
ok 158 listeningPort must be a number
,ok 159 Connection must have clientPort
,ok 160 clientPort must be a number
,ok 161 Connection must have serverPort
,ok 162 serverPort must be a number
,ok 163 reverse connection must have clientPort != 0
,ok 164 reverse connection must have serverPort != 0
,# setup
,2016-03-17 08:40:34.002 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 08:40:34.004 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 08:40:34.007 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:34.007 ThaliTest[1591:2564400] THEMultipeerManager stopping peer
,2016-03-17 08:40:34.009 ThaliTest[1591:2564400] server session: disconnect
2016-03-17 08:40:34.010 ThaliTest[1591:2564400] server session: stateChange:2->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:34.048 ThaliTest[1591:2564400] multipeer manager: stop client timer
,2016-03-17 08:40:34.051 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
,ok 166 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-17 08:40:35.091 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening
2016-03-17 08:40:35.091 ThaliTest[1591:2564400] server: starting B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 08:40:35.092 ThaliTest[1591:2564400] multipeer m,anager: start client restart timer: 0x14ee7e40
,2016-03-17 08:40:35.093 ThaliTest[1591:2564400] THEMultipeerManager initialized peer B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 08:40:35.093 ThaliTest[1591:2564400] jxcore: startUpdateAdvertisingAndListening: success
,ok 167 Can call startUpdateAdvertisingAndListening without error
2016-03-17 08:40:35.096 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 08:40:35.098 ThaliTest[1591:2564400] jxcore: startListeningForAdvertisements: success
,ok 168 Can call startListeningForAdvertisements without error
,2016-03-17 08:40:35.715 ThaliTest[1591:2564215] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:35.717 ThaliTest[1591:2564400] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:35.718 ThaliTest[1591:2,564400] client: server will connect
2016-03-17 08:40:35.718 ThaliTest[1591:2564400] client session: reverseConnect
2016-03-17 08:40:35.718 ThaliTest[1591:2564400] client session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:36.320 ThaliTest[1591:2565168] client session: not connected B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:36.321 ThaliTest[1591:2565168] client session: onLinkFailure: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
,2016-03-17 08:40:36.332 ThaliTest[1591:2565168] client session: disconnect
2016-03-17 08:40:36.334 ThaliTest[1591:2565168] client session: stateChange:1->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:36.346 ThaliTest[1591:2565168] client session: no connect callback (server initiated)
,2016-03-17 08:40:37.326 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:37.326 ThaliTest[1591:2564215] server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D0,6013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:38.022 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:38.023 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:38.023 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:38.165 ThaliTest[1591:2564215] multipeer session: reset timer
,2016-03-17 08:40:38.166 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
,2016-03-17 08:40:38.166 ThaliTest[1591:2564215] server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:40.423 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:40.424 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:40.424 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:41.105 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:41.105 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:41.106 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:4)
,2016-03-17 08:40:41.362 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:41.363 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:41.363 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:43.592 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:43.593 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:43.593 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:44.521 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:44.521 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:44.521 ThaliTest[1591:2564215] server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:45.719 ThaliTest[1591:2564215] jxcore: connect: fail: Timed out awaiting reverse connection
,2016-03-17 08:40:46.685 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:46.685 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:46.686 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:47.732 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:47.733 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:47.733 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:48.731 ThaliTest[1591:2564400] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:48.732 ThaliTest[1591:2564400] client: server will connect
2016-03-17 08:40:48.732 ThaliTest[1591:2564400] client session: reverseConn,ect
2016-03-17 08:40:48.732 ThaliTest[1591:2564400] client session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:49.740 ThaliTest[1591:2565195] client session: not connected B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 08:40:49.740 ThaliTest[1591:2565195] client session: onLinkFailure: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 08:40:49.741 ThaliTest[1591:2565195] client session: disconnect
,2016-03-17 08:40:49.741 ThaliTest[1591:2565195] client session: stateChange:1->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:49.744 ThaliTest[1591:2565195] client session: no connect callback (server initiated)
,2016-03-17 08:40:49.899 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:49.900 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:49.900 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:51.453 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:51.453 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:51.454 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:53.090 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:53.091 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:53.091 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:54.533 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:54.534 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:54.534 ThaliTest[1591:2564215], server: rejecting invitation from B834405C-4BB1-4DDE-BBBE-95797DDD18CB due to previous generation (B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6 != B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:5)
,2016-03-17 08:40:55.094 ThaliTest[1591:2564215] multipeer manager: restart client
,2016-03-17 08:40:55.114 ThaliTest[1591:2564215] client: found existing peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,2016-03-17 08:40:55.254 ThaliTest[1591:2564215] multipeer session: reset timer
2016-03-17 08:40:55.255 ThaliTest[1591:2564215] server: disconnecting to refresh session (B834405C-4BB1-4DDE-BBBE-95797DDD18CB)
2016-03-17 08:40:55.255 ThaliTest[1591:2564215] server session: connect
2016-03-17 08:40:55.255 ThaliTest[1591:2564215] server session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:6
,2016-03-17 08:40:55.266 ThaliTest[1591:2564215] server: accepting invitation B834405C-4BB1-4DDE-BBBE-95797DDD18CB
,2016-03-17 08:40:57.545 ThaliTest[1591:2565354] server session: p2p link connected
,2016-03-17 08:40:57.991 ThaliTest[1591:2564215] server relay: connected (to port: 63173)
2016-03-17 08:40:57.993 ThaliTest[1591:2564215] server session: stateChange:1->2 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:6
2016-03-17 08:40:57.993 ThaliTest[1591:2564215] jxcore: connect: success
{ clientPort: 63182, serverPort: 63173, listeningPort: 0 }
Reverse connection
,reverseData
,reverseSend
,reverseData
,reverseData
,reverseData
ok 169 received should match sent reverse
,# setup
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,reverseData
,2016-03-17 08:40:59.135 ThaliTest[1591:2564400] jxcore: stopListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-03-17 08:40:59.137 ThaliTest[1591:2564400], jxcore: stopListeningForAdvertisements: success
ok 170 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 08:40:59.139 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening
2016-03-17 08:40:59.139 ThaliTest[1591:2564400] ,THEMultipeerManager stopping peer
2016-03-17 08:40:59.140 ThaliTest[1591:2564400] server session: disconnect
2016-03-17 08:40:59.140 ThaliTest[1591:2564400] server session: stateChange:2->0 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:6
,2016-03-17 08:40:59.175 ThaliTest[1591:2564400] multipeer manager: stop client timer
2016-03-17 08:40:59.176 ThaliTest[1591:2564400] jxcore: stopAdvertisingAndListening: success
ok 171 Should be able to call stopAdvertisingAndListening in teardown
,# 39. can get the network status before starting
,# teardown
,ok 172 network status should have certain non-empty properties
,# setup
,# 40. #generatePreambleAndBeacons bad args
,# teardown
,ok 173 publicKeysToNotify cannot be null
,ok 174 ecdh for local device cannot be null
,ok 175 milliseconds cannot be less than 0
,ok 176 milliseconds cannot be 0
,ok 177 milliseconds cannot be greater than one_day
,# setup
,# 41. #generatePreambleAndBeacons empty keys to notify
,# teardown
,ok 178 should be equal
,# setup
,# 42. #generatePreambleAndBeacons multiple keys to notify
,# teardown
,ok 179 should be equal
ok 180 should be equal
,ok 181 (unnamed assert)
,ok 182 should be equal
,# setup
,# 43. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,# teardown
,ok 183 should throw
,# setup
,# 44. #parseBeacons invalid expiration in beaconStreamWithPreAmble
,# teardown
,ok 184 Preamble expiration must be a 64 bit integer
,# setup
,# 45. #parseBeacons expiration out of range lower
,# teardown
,ok 185 Expiration out of range
,# setup
,# 46. #parseBeacons expiration out of range lower
,# teardown
,ok 186 Expiration out of range
,# setup
,# 47. #parseBeacons no beacons returns null
,# teardown
,ok 187 should be equal
,# setup
,# 48. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,# teardown
,ok 188 Malformed encrypted beacon key ID
,# setup
,# 49. #parseBeacons addressBookCallback fails decrypt
,# teardown
,ok 189 should be equal
,# setup
,# 50. #parseBeacons addressBookCallback returns no matches
,# teardown
,ok 190 should be equal
ok 191 should be equal
,# setup
,# 51. #parseBeacons addressBookCallback returns spurious match
,# teardown
,ok 192 should be equal
,ok 193 should be equal
,# setup
,# 52. #parseBeacons addressBookCallback returns public key
,# teardown
,ok 194 should be equal
ok 195 (unnamed assert)
,# setup
,# 53. #parseBeacons with beacons both for and not for the user
,# teardown
,ok 196 should be equal
ok 197 (unnamed assert)
,# setup
,# 54. Start and stop ThaliNotificationServer
,# teardown
,ok 198 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 199 ThaliMobile.StopAdvertisingAndListening should be called once
,# setup
,# 55. Pass an empty array to ThaliNotificationServer.start
,# teardown
,ok 200 StartUpdateAdvertisingAndListening should not be called
,ok 201 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 202 no error
,ok 203 should be 204
,# setup
,# 56. Pass a string to ThaliNotificationServer.start
,# teardown
,ok 204 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 57. Pass an empty parameter to ThaliNotificationServer.start
,# teardown
,ok 205 StartUpdateAdvertisingAndListening should not be called
,# setup
,# 58. Make an HTTP request to /NotificationBeacons
,# teardown
,ok 206 no error
,ok 207 should be 200
,ok 208 should be equal
,ok 209 should be equal
,ok 210 (unnamed assert)
,ok 211 no error
ok 212 should be 204
,# setup
,# 59. Make an HTTP request to /NotificationBeacons (no keys)
,# teardown
,ok 213 error should be null
,ok 214 should be 204
,# setup
,# 60. Make an HTTP request to /NotificationBeacons before calling start
,# teardown
,ok 215 should be 404
,# setup
,# 61. #testThaliPeerAction - test getters
,# teardown
,ok 216 getPeerIdentifier
,ok 217 getConnectionType
,ok 218 getActionType
,ok 219 getActionState
,# setup
,# 62. #testThaliPeerAction - start and kill
,# teardown
,ok 220 initial state
,ok 221 after start
,ok 222 after kill
,# setup
,# 63. #testThaliPeerAction - double start
,# teardown
,ok 223 should be equal
,# setup
,# 64. #testThaliPeerAction - start after kill
,# teardown
,ok 224 clean kill
,ok 225 should be equal
,# setup
,# 65. #testThaliPeerAction - make sure ids are unique
,# teardown
,ok 226 should not be equal
,# setup
,# 66. Test PeerConnectionInformation basics
,# teardown
,ok 227 getHostAddress works
,ok 228 getPortNumber works
,ok 229 getSuggestedTCPTimeout works
,# setup
,# 67. Test PeerDictionary basic functionality
,# teardown
,ok 230 Entry counter must be 1
,ok 231 Size must be 1
,ok 232 Entry counter must be 2
,ok 233 Size must be 2
,ok 234 Entry2 should not be found
,ok 235 Size must be 1
,ok 236 Size must be 0
,ok 237 entry not found must be thrown
,# setup
,# 68. Test PeerDictionary with multiple entries.
,# teardown
,ok 238 Size must be100
,ok 239 Entries between 20 and MAXSIZE + 20 should exist
,ok 240 WAITING state entry should not be removed
,# setup
,# 69. RESOLVED entries are removed before WAITING state entry.
,# teardown
,ok 241 Entries between 6 and MAXSIZE + 4 should exist
,ok 242 Size should be MAXSIZE
,ok 243 Size should be MAXSIZE+6
,# setup
,# 70. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,# teardown
,ok 244 WAITING state entry should not be removed
,ok 245 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 246 Size should be MAXSIZE
,ok 247 entryCounter should be MAXSIZE+6
,# setup
,# 71. When CONTROLLED_BY_POOL entry is removed and kill is called.
,# teardown
,ok 248 Kill should be called once
ok 249 Size should be 100
,# setup
,# 72. #ThaliPeerPoolInterface - bad enqueues
,# teardown
,ok 250 null arg
,ok 251 wrong arg type
,ok 252 wrong state
,# setup
,# 73. #ThaliPeerPoolInterface - do not allow same object type
,# teardown
,ok 253 good enqueue
,ok 254 should be equal
,# setup
,# 74. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,# teardown
,ok 255 good enqueue
,ok 256 2nd good enqueue
,ok 257 we are in the pool
,ok 258 We are out of the pool
,ok 259 Action was killed
,ok 260 The original kill was called too
,ok 261 second item is still in queue
,# setup
,# 75. compareBufferArrays
,# teardown
,ok 262 should throw
,ok 263 should throw
,ok 264 (unnamed assert)
,ok 265 (unnamed assert)
,ok 266 (unnamed assert)
,ok 267 (unnamed assert)
,ok 268 (unnamed assert)
,# setup
,# 76. Call start twice and get error
,# teardown
,ok 269 should throw
,# setup
,# 77. Start and make sure it runs
,# teardown
,# setup
,# 78. Make sure getTimeWhenRun is right after start
,# teardown
,ok 270 (unnamed assert)
,# setup
,# 79. Make sure getTimeWhenRun is -1 after function is called
,# teardown
,ok 271 should be equal
,# setup
,# 80. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
,# teardown
,ok 272 should be equal
,ok 273 should be equal
,ok 274 should throw
,# setup
,# 81. Test TransientState
,# teardown
,ok 275 should throw
,ok 276 should throw
,ok 277 should be equal
,ok 278 should be equal
,ok 279 should be equal
,ok 280 should be equal
,ok 281 (unnamed assert)
,ok 282 (unnamed assert)
,# setup
,# 82. No peers and empty database
,# teardown
,ok 283 verify failed
ok 284 constructor called once
,ok 285 constructor called with right args
,ok 286 match start arg
,ok 287 start called once
,ok 288 stop called once
,ok 289 stop after start
,# setup
,# 83. One peer and empty DB
,# teardown
,ok 290 verify failed
ok 291 constructor called once
,ok 292 constructor called with right args
,ok 293 match start arg
,ok 294 start called once
,ok 295 stop called once
,ok 296 stop after start
,# setup
,# 84. One peer with _Local set behind current seq
,# teardown
,ok 297 verify failed
,ok 298 constructor called once
,ok 299 constructor called with right args
,ok 300 match start arg
,ok 301 start called once
,ok 302 stop called once
,ok 303 stop after start
,# setup
,# 85. One peer with _Local set equal to current seq
,# teardown
,ok 304 verify failed
ok 305 constructor called once
,ok 306 constructor called with right args
,ok 307 match start arg
,ok 308 start called once
,ok 309 stop called once
,ok 310 stop after start
,# setup
,# 86. One peer with _Local set ahead of current seq (and no this should not happen)
,# teardown
,ok 311 verify failed
ok 312 constructor called once
,ok 313 constructor called with right args
,ok 314 match start arg
,ok 315 start called once
,ok 316 stop called once
,ok 317 stop after start
,# setup
,# 87. Three peers, one not in DB, one behind and one ahead
,# teardown
,ok 318 verify failed
ok 319 constructor called once
,ok 320 constructor called with right args
,ok 321 match start arg
,ok 322 start called once
,ok 323 stop called once
,ok 324 stop after start
,# setup
,# 88. More than maximum peers, make sure we only send maximum allowed
,# teardown
,ok 325 verify failed
,ok 326 constructor called once
,ok 327 constructor called with right args
,ok 328 match start arg
,ok 329 start called once
,ok 330 stop called once
,ok 331 stop after start
,# setup
,# 89. two peers with empty DB, update the doc
,# teardown
,ok 332 verify failed
ok 333 constructor called once
,ok 334 constructor called with right args
,ok 335 last start before stop
,ok 336 empty first start
,ok 337 full second start
,ok 338 only 2 timers
,# setup
,# 90. add doc and make sure tokens refresh when they expire
,# teardown
,ok 339 verify failed
,ok 340 constructor called once
,ok 341 constructor called with right args
,ok 342 start before stop
,ok 343 We got at least 3 calls to start
,ok 344 at least 3
,ok 345 default 1
,ok 346 1 run
,ok 347 default 2
,ok 348 2 run
,ok 349 default 3
,# setup
,# 91. start and stop and start and stop
,# teardown
,ok 350 start out null
,ok 351 back to null
,ok 352 still null
,ok 353 verify failed
,ok 354 constructor called once
,ok 355 constructor called with right args
,ok 356 first start before first stop
,ok 357 first stop before second start
,ok 358 second start before second stop
,# setup
,# 92. two identical starts in a row
,# teardown
,ok 359 verify failed
,ok 360 constructor called once
,ok 361 constructor called with right args
,ok 362 (unnamed assert)
,# setup
,# 93. two different starts in a row
,# teardown
,ok 363 verify failed
ok 364 constructor called once
,ok 365 constructor called with right args
,ok 366 (unnamed assert)
,ok 367 (unnamed assert)
,# setup
,# 94. two stops and a start and two stops
,# teardown
,ok 368 verify failed
ok 369 constructor called once
,ok 370 constructor called with right args
,ok 371 start before stop
,# setup
,# 95. we properly enqueue requests so no then needed
,# teardown
,ok 372 verify failed
ok 373 constructor called once
,ok 374 constructor called with right args
,ok 375 start before stop
,# setup
,# 96. test calculateSeqPointKeyId
,# teardown
,ok 376 should be equal
,ok 377 should be equal
,# setup
,# 97. can create servers manager
,# teardown
,ok 378 serversManager must not be null
,ok 379 serversManager must be an object
,# setup
,# 98. calling stop without start causes error
,# teardown
,ok 380 We need to call start first
,# setup
,# 99. can start/stop servers manager
,# teardown
,ok 381 port must be in range
,# setup
,# 100. starting twice resolves with listening port
,# teardown
,ok 382 second start should return same port
,# setup
,# 101. terminateIncomingConnection will terminate a connection
,# teardown
,ok 383 we should be connected
,ok 384 now we are disconnected
,# setup
,# 102. terminate an Outgoing connection will terminate the server
,# teardown
,# setup
,# 103. terminate an Outgoing connection with wrong arguments is not harmful
,# teardown
,# setup
,# 104. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,ok 385 should be in started state
,# teardown
,ok 386 peer identifier should match
,ok 387 host address should match
,ok 388 port should match
,ok 389 host address should be null
,ok 390 port should should be null
,# setup
,ok 391 should not be in started state
,# 105. #startUpdateAdvertisingAndListening should use different USN after every invocation
,ok 392 should be in started state
,# teardown
,ok 393 USN should have changed from the first one
,ok 394 when receiving the second byebye, the first USN should be already set
,# setup
,ok 395 should not be in started state
,# 106. messages with invalid location or USN should be ignored
,ok 396 should be in started state
,# teardown
,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
,ok 397 should not have emitted with invalid port
,WARN thaliWifiInfrastructure Received an invalid USN value: 
,ok 398 should not have emitted with invalid USN
,# setup
,ok 399 should not be in started state
,# 107. verify that Thali-specific messages are filtered correctly
,ok 400 should be in started state
,# teardown
,ok 401 irrelevant messages should be ignored
,ok 402 relevant messages should not be ignored
,ok 403 messages from this device should be ignored
,# setup
,ok 404 should not be in started state
,# 108. #startListeningForAdvertisements should fail if start not called
,ok 405 should be in started state
,# teardown
,ok 406 specific error should be returned
,# setup
,ok 407 should not be in started state
,# 109. #startUpdateAdvertisingAndListening should fail if start not called
,ok 408 should be in started state
,# teardown
,ok 409 specific error should be returned
,# setup
,ok 410 should not be in started state
,# 110. #start should fail if called twice in a row
,ok 411 should be in started state
,# teardown
,ok 412 specific error should be received
,# setup
,ok 413 should not be in started state
,# 111. should not be started after stop is called
,ok 414 should be in started state
,# teardown
,ok 415 should not be started
,ok 416 should not be listening
,ok 417 should not target listening
,ok 418 should not be advertising
,ok 419 should not target advertising
,# setup
,ok 420 should not be in started state
,# 112. #startUpdateAdvertisingAndListening should fail invalid router has been passed
,ok 421 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,ok 422 specific error should be received
,# setup
,ok 423 should not be in started state
,# 113. #startUpdateAdvertisingAndListening should fail if router server starting fails
,ok 424 should be in started state
,# teardown
,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
,ok 425 specific error expected
,# setup
,ok 426 should not be in started state
,# 114. #startUpdateAdvertisingAndListening should start hosting given router object
,ok 427 should be in started state
,# teardown
,ok 428 server should respond with code 200
,# setup
,ok 429 should not be in started state
,# 115. #stop can be called multiple times in a row
,ok 430 should be in started state
,# teardown
,ok 431 should be in stopped state
,ok 432 should still be in stopped state
,# setup
,ok 433 should not be in started state
,# 116. #startListeningForAdvertisements can be called multiple times in a row
,ok 434 should be in started state
,# teardown
,ok 435 should be in listening state
,ok 436 should still be in listening state
,# setup
,ok 437 should not be in started state
,# 117. #stopListeningForAdvertisements can be called multiple times in a row
,ok 438 should be in started state
,# teardown
,ok 439 should not be in listening state
,ok 440 should still not be in listening state
,# setup
,ok 441 should not be in started state
,# 118. #stopAdvertisingAndListening can be called multiple times in a row
,ok 442 should be in started state
,# teardown
,ok 443 should not be in advertising state
,ok 444 should still not be in advertising state
,# setup
,ok 445 should not be in started state
,# 119. functions are run from a queue in the right order
,ok 446 should be in started state
,# teardown
,ok 447 call order must match
,# setup
,ok 448 should not be in started state
,# 120. #ThaliPeerPoolDefault - single action
,# teardown
,ok 449 is an agent
,ok 450 enqueue is fine
,ok 451 Everything should be off the queue
,# setup
,# 121. #ThaliPeerPoolDefault - multiple actions
,# teardown
,ok 452 is an agent
,ok 453 first enqueue is fine
,ok 454 is an agent
,ok 455 second enqueue is fine
,ok 456 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 457 Queue is empty
,Tests Complete
,Total: 0	Passed: 0	Failed: 0
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
