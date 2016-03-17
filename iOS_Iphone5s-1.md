#### Test 62509094b685d58_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8401581E-E020-4686-B48F-037234285630/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8401581E-E020-4686-B48F-037234285630/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094b685d58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52001"
,(lldb)     command script import "/tmp/8401581E-E020-4686-B48F-037234285630/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 12:27:54.018 ThaliTest[1662:2662980] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1D3FAB11-AF48-4DDF-AE41-A64C36F0F360/Library/Cookies/Cookies.binarycookies
,2016-03-17 12:27:54.422 ThaliTest[1662:2662980] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 12:27:54.424 ThaliTest[1662:2662980] Multi-tasking -> Device: YES, App: YES
,2016-03-17 12:27:54.449 ThaliTest[1662:2662980] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 12:27:56.143 ThaliTest[1662:2662980] Using UIWebView
,2016-03-17 12:27:56.151 ThaliTest[1662:2662980] [CDVTimer][handleopenurl] 0.452995ms
,2016-03-17 12:27:56.160 ThaliTest[1662:2662980] [CDVTimer][intentandnavigationfilter] 8.516014ms
2016-03-17 12:27:56.161 ThaliTest[1662:2662980] [CDVTimer][gesturehandler] 0.374973ms
2016-03-17 12:27:56.161 ThaliTest[1662:2662980] [CDVTimer][TotalPluginS,tartup] 11.157036ms
,2016-03-17 12:28:02.246 ThaliTest[1662:2662980] Resetting plugins due to page load.
,2016-03-17 12:28:05.297 ThaliTest[1662:2662980] Finished load of: file:///var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/index.html
,2016-03-17 12:28:05.529 ThaliTest[1662:2662980] JXcore Cordova plugin initializing
,2016-03-17 12:28:05.530 ThaliTest[1662:2663157] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 12:28:10.552 ThaliTest[1662:2663157] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 12:28:10.552 ThaliTest[1662:2663157] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 12:28:10.553 ThaliTest[1662:2663157] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 12:28:10.556 ThaliTest[1662:2663157] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EA9AB4A4-9C34-4A45-9605-4F4089BD3CBB/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 12:28:21.141 ThaliTest[1662:2662980] THREAD WARNING: ['JXcore'] took '7620.527588' ms. Plugin should use a background thread.
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
,2016-03-17 12:31:30.222 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements
,2016-03-17 12:31:30.225 ThaliTest[1662:2663157] multipeer manager: start client restart timer: 0x14e74720
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 12:31:30.229 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:30.233 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements
2016-03-17 12:31:30.234 ThaliTest[1662:2663157] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 12:31:30.248 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-17 12:31:30.508 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 12:31:30.511 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:30.514 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening
2016-03-17 12:31:30.515 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
2016-03-17 12:31:30.515 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 12:31:30.727 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements
2016-03-17 12:31:30.728 ThaliTest[1662:2663157] multipeer manager: start client restart timer: 0x14e74720
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdat,eNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 12:31:30.730 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-17 12:31:30.734 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discove,ryActive":true}
2016-03-17 12:31:30.739 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 12:31:32.259 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements
2016-03-17 12:31:32.260 ThaliTest[1662:2663157] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}
,2016-03-17 12:31:32.262 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 12:31:32.267 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening
2016-03-17 12:31:32.268 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
2016-03-17 12:3,1:32.268 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 12:31:32.749 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening
2016-03-17 12:31:32.750 ThaliTest[1662:2663157] server: starting 073917DB-1D47-40B2-A8E8-69D166708C51:1
2016-03-17 12:31:32.751 ThaliTest[1662:2663157] multipeer m,anager: start client restart timer: 0x14e74720
2016-03-17 12:31:32.752 ThaliTest[1662:2663157] THEMultipeerManager initialized peer 073917DB-1D47-40B2-A8E8-69D166708C51:1
2016-03-17 12:31:32.752 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 12:31:32.769 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening
,2016-03-17 12:31:32.772 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
,2016-03-17 12:31:32.783 ThaliTest[1662:2663157] multipeer manager: stop client timer
,2016-03-17 12:31:32.786 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-17 12:31:33.060 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 12:31:33.063 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:33.066 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening
2016-03-17 12:31:33.066 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
2016-03-17 12:31:33.066 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening: suc,cess
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 12:31:33.287 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening
2016-03-17 12:31:33.288 ThaliTest[1662:2663157] server: starting 073917DB-1D47-40B2-A8E8-69D166708C51:2
2016-03-17 12:31:33.288 ThaliTest[1662:2663157] multipeer m,anager: start client restart timer: 0x14e74720
2016-03-17 12:31:33.289 ThaliTest[1662:2663157] THEMultipeerManager initialized peer 073917DB-1D47-40B2-A8E8-69D166708C51:2
2016-03-17 12:31:33.290 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening: success
,ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 12:31:33.293 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening
,2016-03-17 12:31:33.294 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
2016-03-17 12:31:33.295 ThaliTest[1662:2663157] multipeer manager: stop client timer
2016-03-17 12:31:33.296 ThaliTest[1662:2663157] server: starting 073917DB-1D47-40B2-A8E,8-69D166708C51:3
2016-03-17 12:31:33.297 ThaliTest[1662:2663157] multipeer manager: start client restart timer: 0x14e74720
2016-03-17 12:31:33.297 ThaliTest[1662:2663157] THEMultipeerManager initialized peer 073917DB-1D47-40B2-A8E8-69D166708C51:3
2016-0,3-17 12:31:33.297 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-17 12:31:34.697 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 12:31:34.700 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:34.703 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening
2016-03-17 12:31:34.704 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
2016-03-17 12:31:34.704 ThaliTest[1662:2663157] multipeer manager: stop client timer
20,16-03-17 12:31:34.705 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 12:31:35.277 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening
2016-03-17 12:31:35.278 ThaliTest[1662:2663157] server: starting 073917DB-1D47-40B2-A8E8-69D166708C51:4
2016-03-17 12:31:35.279 ThaliTest[1662:2663157] multipeer m,anager: start client restart timer: 0x14e74720
2016-03-17 12:31:35.280 ThaliTest[1662:2663157] THEMultipeerManager initialized peer 073917DB-1D47-40B2-A8E8-69D166708C51:4
2016-03-17 12:31:35.280 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-17 12:31:35.284 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-17 12:31:35.287 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:37.577 ThaliTest[1662:2662980] client: found new peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
ok 147 peers must be an array
,ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 12:31:38.494 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 12:31:38.496 ThaliTest[1662:2663157] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 12:31:38.500 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening
2016-03-17 12:31:38.500 ThaliTest[1662:2663157] THEMultipeerManager stopping peer
2016-03-17 12:31:38.501 ThaliTest[1662:2663157] multipeer manager: stop client timer
20,16-03-17 12:31:38.501 ThaliTest[1662:2663157] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 12:31:38.863 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndListening
2016-03-17 12:31:38.864 ThaliTest[1662:2663157] server: starting 073917DB-1D47-40B2-A8E8-69D166708C51:5
2016-03-17 12:31:38.865 ThaliTest[1662:2663157] multipeer m,anager: start client restart timer: 0x14e74720
2016-03-17 12:31:38.865 ThaliTest[1662:2663157] THEMultipeerManager initialized peer 073917DB-1D47-40B2-A8E8-69D166708C51:5
2016-03-17 12:31:38.866 ThaliTest[1662:2663157] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 12:31:38.868 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 12:31:38.872 ThaliTest[1662:2663157] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 12:31:39.891 ThaliTest[1662:2662980] client: found new peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"32B08C85-F042-4FA8-ADF8-9E6C0A7C58,B7:4","pleaseConnect":0}]
,2016-03-17 12:31:39.897 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:39.900 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:31:39.900 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:31:39.900 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
,2016-03-17 12:31:41.495 ThaliTest[1662:2663550] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:41.496 ThaliTest[1662:2663550] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:31:41.4,96 ThaliTest[1662:2663550] client session: disconnect
2016-03-17 12:31:41.496 ThaliTest[1662:2663550] client session: stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:41.497 ThaliTest[1662:2663550] client session: no connect callb,ack (server initiated)
,2016-03-17 12:31:49.901 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-17 12:31:52.907 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:52.908 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:31:52.908 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:31:52.908 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
,2016-03-17 12:31:53.424 ThaliTest[1662:2663533] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:53.424 ThaliTest[1662:2663533] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:31:53.4,24 ThaliTest[1662:2663533] client session: disconnect
2016-03-17 12:31:53.424 ThaliTest[1662:2663533] client session: stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:31:53.425 ThaliTest[1662:2663533] client session: no connect callback (server initiated)
,2016-03-17 12:31:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:31:58.890 ThaliTest[1662:2662980] client: found updated peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5","pleaseConnect":0}]
,2016-03-17 12:32:02.909 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-17 12:32:05.920 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:32:05.921 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:32:05.921 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:32:05.922 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:06.726 ThaliTest[1662:2663533] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:32:06.727 ThaliTest[1662:2663533] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:32:06.7,28 ThaliTest[1662:2663533] client session: disconnect
,2016-03-17 12:32:06.728 ThaliTest[1662:2663533] client session: stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:32:06.732 ThaliTest[1662:2663533] client session: no connect callback (server initiated)
,2016-03-17 12:32:15.923 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-17 12:32:18.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:32:18.891 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:18.933 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:32:18.934 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:32:18.934 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:32:18.934 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:19.107 ThaliTest[1662:2663533] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:19.111 ThaliTest[1662:2663533] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:32:19.111 ThaliTest[1662:2663533] client session: disconnect
2016-03-17 12:32:19.111 ThaliTest[1662:2663533] client session:, stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:32:19.112 ThaliTest[1662:2663533] client session: no connect callback (server initiated)
,2016-03-17 12:32:28.935 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-17 12:32:31.946 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:32:31.947 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:32:31.947 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:32:31.948 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:32.730 ThaliTest[1662:2663533] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:32:32.731 ThaliTest[1662:2663533] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:32:32.7,31 ThaliTest[1662:2663533] client session: disconnect
2016-03-17 12:32:32.731 ThaliTest[1662:2663533] client session: stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:32.735 ThaliTest[1662:2663533] client session: no connect callback (server initiated)
,2016-03-17 12:32:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:32:38.891 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:41.948 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-17 12:32:44.954 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:32:44.955 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:32:44.956 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:32:44.956 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:45.308 ThaliTest[1662:2663533] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:32:45.309 ThaliTest[1662:2663533] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:32:45.3,09 ThaliTest[1662:2663533] client session: disconnect
,2016-03-17 12:32:45.310 ThaliTest[1662:2663533] client session: stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:45.313 ThaliTest[1662:2663533] client session: no connect callback (server initiated)
,2016-03-17 12:32:54.957 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-17 12:32:57.966 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:32:57.967 ThaliTest[1662:2663157] client: server will connect
2016-03-17 12:32:57.967 ThaliTest[1662:2663157] client session: reverseConn,ect
2016-03-17 12:32:57.968 ThaliTest[1662:2663157] client session: stateChange:0->1 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:32:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:32:58.898 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:33:07.969 ThaliTest[1662:2662980] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-17 12:33:10.979 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:33:10.980 ThaliTest[1662:2663157] client: already connect(ing/ed) to 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:33:10.981 Thali,Test[1662:2663157] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-17 12:33:13.993 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:33:13.994 ThaliTest[1662:2663157] client: already connect(ing/ed) to 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:33:13.994 Thali,Test[1662:2663157] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-17 12:33:17.011 ThaliTest[1662:2663157] jxcore: connect 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:33:17.012 ThaliTest[1662:2663157] client: already connect(ing/ed) to 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:4
2016-03-17 12:33:17.013 Thali,Test[1662:2663157] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,WARN testThaliMobileNative Too many connect retries!
,2016-03-17 12:33:18.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:33:18.889 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:33:30.963 ThaliTest[1662:2663931] client session: not connected 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:33:30.963 ThaliTest[1662:2663931] client session: onLinkFailure: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7
2016-03-17 12:33:30.9,63 ThaliTest[1662:2663931] client session: disconnect
2016-03-17 12:33:30.964 ThaliTest[1662:2663931] client session: stateChange:1->0 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
2016-03-17 12:33:30.964 ThaliTest[1662:2663931] client session: no connect callb,ack (server initiated)
,2016-03-17 12:33:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:33:38.891 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:33:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:33:58.891 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:34:18.865 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:34:18.889 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:34:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:34:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:34:58.880 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:35:18.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:35:18.882 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:35:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:35:38.880 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:35:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:35:58.881 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:36:18.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:36:18.882 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:36:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:36:38.882 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:36:58.867 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:36:58.881 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:37:18.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:37:18.881 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:37:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:37:38.881 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:37:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:37:58.879 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:38:18.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:38:18.882 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:38:38.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:38:38.880 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:38:58.866 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:38:58.885 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:39:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:39:18.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:39:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:39:38.850 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:39:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:39:58.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:40:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:40:18.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:40:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:40:38.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:40:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:40:58.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:41:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:41:18.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:41:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:41:38.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:41:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:41:58.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:42:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:42:18.853 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:42:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:42:38.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:42:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:42:58.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:43:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:43:18.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:43:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:43:38.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:43:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:43:58.857 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:44:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:44:18.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:44:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:44:38.850 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:44:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:44:58.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:45:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:45:18.850 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:45:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:45:38.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:45:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:45:58.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:46:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:46:18.848 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:46:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:46:38.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:46:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:46:58.850 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:47:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:47:18.850 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:47:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:47:38.853 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:47:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:47:58.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:48:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:48:18.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:48:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:48:38.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:48:58.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:48:58.852 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:49:18.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:49:18.853 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5
,2016-03-17 12:49:38.836 ThaliTest[1662:2662980] multipeer manager: restart client
,2016-03-17 12:49:38.851 ThaliTest[1662:2662980] client: found existing peer: 32B08C85-F042-4FA8-ADF8-9E6C0A7C58B7:5

```
