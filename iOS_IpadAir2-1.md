#### Test 625481247756efd_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/709AA102-6B27-4B96-A45E-E5AF2922D079/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/709AA102-6B27-4B96-A45E-E5AF2922D079/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49422"
,(lldb)     command script import "/tmp/709AA102-6B27-4B96-A45E-E5AF2922D079/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-11 16:05:44.300 ThaliTest[1197:1771995] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD5912FB-01BA-47DC-B70D-CB050A03F05B/Library/Cookies/Cookies.binarycookies
,2016-03-11 16:05:44.636 ThaliTest[1197:1771995] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 16:05:44.637 ThaliTest[1197:1771995] Multi-tasking -> Device: YES, App: YES
,2016-03-11 16:05:44.653 ThaliTest[1197:1771995] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 16:05:46.236 ThaliTest[1197:1771995] Using UIWebView
,2016-03-11 16:05:46.243 ThaliTest[1197:1771995] [CDVTimer][handleopenurl] 0.401020ms
,2016-03-11 16:05:46.251 ThaliTest[1197:1771995] [CDVTimer][intentandnavigationfilter] 7.047951ms
,2016-03-11 16:05:46.252 ThaliTest[1197:1771995] [CDVTimer][gesturehandler] 0.335991ms
2016-03-11 16:05:46.252 ThaliTest[1197:1771995] [CDVTimer][TotalPluginStartup] 9.518027ms
,2016-03-11 16:05:52.960 ThaliTest[1197:1771995] Resetting plugins due to page load.
,2016-03-11 16:05:56.003 ThaliTest[1197:1771995] Finished load of: file:///var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/index.html
,2016-03-11 16:05:56.205 ThaliTest[1197:1771995] JXcore Cordova plugin initializing
,2016-03-11 16:05:56.206 ThaliTest[1197:1772227] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 16:06:09.405 ThaliTest[1197:1772227] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 16:06:09.406 ThaliTest[1197:1772227] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-11 16:06:09.406 ThaliTest[1197:1772227] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 16:06:09.407 ThaliTest[1197:1772227] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C4E6DB22-C024-4CD8-94DB-999D02670D0E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,TAP version 13

,# setup

,# 1. closeAll can close even when connections open

,# teardown

,ok 1 not possible to connect to the server anymore

,# setup

,# 2. closeAll with promise

,# teardown

,ok 2 not possible to connect to the server anymore

,# setup

,# 3. multiplex can send data

,# teardown

,ok 3 String should be length:200

,# setup

,# 4. enqueue and run in order

,# teardown

,ok 4 firstPromise setTimeout

,ok 5 firstPromise result

,ok 6 firstPromise testValue

,ok 7 secondPromise setTimeout

,ok 8 secondPromise result

,ok 9 secondPromise testValue

,ok 10 thirdPromise in promise

,ok 11 thirdPromise result

,ok 12 thirdPromise testValue

,# setup

,# 5. enqueueAtTop and run backwards

,# teardown

,ok 13 thirdPromise - first to run

,ok 14 thirdPromise - in resolve

,ok 15 secondPromise - second to run

,ok 16 secondPromise - in catch

,ok 17 firstPromise - third to run

,ok 18 firstPromise - in then

,ok 19 testing promises

,# setup

,# 6. mix enqueue and enqueueAtTop

,# teardown

,ok 20 fourth

,ok 21 fourth

,ok 22 second

,ok 23 secondPromise - in then

,ok 24 first

,ok 25 firstPromise - in catch

,ok 26 third

,ok 27 thirdPromise - in then

,ok 28 testingPromises

,# setup

,# 7. queues handled independently

,# teardown

,ok 29 all short operations completed before the long resolves

,# setup

,# 8. basic

,# teardown

,ok 30 sane

,# setup

,# 9. another

,# teardown

,ok 31 sane

,# setup

,# 10. #startListeningForAdvertisements should fail if start not called

,# teardown

,ok 32 specific error should be returned

,# setup

,ok 33 error should be null

,ok 34 error should be null

,# 11. #startUpdateAdvertisingAndListening should fail if start not called

,# teardown

,ok 35 specific error should be returned

,# setup

,ok 36 error should be null

,ok 37 error should be null

,# 12. should be able to call #stopListeningForAdvertisements many times

,# teardown

,2016-03-11 16:09:33.806 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:33.809 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,ok 38 error should be null

,ok 39 error should be null

,2016-03-11 16:09:33.814 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:33.816 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,ok 40 error should be null

,ok 41 error should be null

,# setup

,2016-03-11 16:09:33.961 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:33.961 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:33.962 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:33.963 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:33.965 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,ok 42 error should be null

,ok 43 error should be null

,# 13. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-11 16:09:34.258 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
,2016-03-11 16:09:34.260 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:34.262 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
,ok 44 error should be null

,ok 45 error should be null

,2016-03-11 16:09:34.290 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:34.292 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
,ok 46 error should be null

,ok 47 error should be null

,# setup

,2016-03-11 16:09:34.586 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:34.587 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:34.587 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:34.588 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,2016-03-11 16:09:34.589 ThaliTest[1197:1772227] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:34.592 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-11 16:09:35.044 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:35.045 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:1
,2016-03-11 16:09:35.047 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
2016-03-11 16:09:35.047 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:1
2016-03-11 16:09:35.048 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
,ok 50 error should be null

,ok 51 error should be null

,2016-03-11 16:09:35.081 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:35.081 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:35.082 ThaliTest[1197:1772227] multipeer manager: stop client timer
2016-03-11 16:09:35.083 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:2
,2016-03-11 16:09:35.084 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
2016-03-11 16:09:35.084 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:2
2016-03-11 16:09:35.085 ,ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
,ok 52 error should be null

,ok 53 error should be null

,# setup

,2016-03-11 16:09:35.201 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:35.201 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:35.202 ThaliTest[1197:1772227] multipeer manager: stop client timer
2016-03-11 16:09:35.203 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:35.204 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:35.206 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 54 error should be null

,ok 55 error should be null

,# 15. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-11 16:09:35.734 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:35.735 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
2016-03-11 16:09:35.736 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,ok 56 error should be null

,ok 57 error should be null

,2016-03-11 16:09:35.742 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:35.743 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:35.743 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,ok 58 error should be null

,ok 59 error should be null

,# setup

,2016-03-11 16:09:36.139 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:36.140 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:36.140 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:36.141 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:36.143 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,ok 60 error should be null

,ok 61 error should be null

,# 16. #start should fail if called twice in a row

,# teardown

,ok 62 first call should succeed

,ok 63 first call should succeed

,ok 64 specific error should be returned

,# setup

,2016-03-11 16:09:38.099 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:38.099 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:38.100 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:38.101 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:38.103 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,ok 65 error should be null

,ok 66 error should be null

,# 17. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-11 16:09:38.636 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
,2016-03-11 16:09:38.637 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:38.638 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
,2016-03-11 16:09:38.657 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:38.658 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:3
,2016-03-11 16:09:38.659 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:3
2016-03-11 16:09:38.659 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
,ok 67 called only once

,ok 68 discovery state matches

,ok 69 advertising state matches

,# setup

,2016-03-11 16:09:38.804 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:38.805 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:38.805 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:38.806 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,2016-03-11 16:09:38.808 ThaliTest[1197:1772227] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-11 16:09:38.811 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 70 error should be null

,ok 71 error should be null

,# 18. does not send duplicate availability changes

,# teardown

,ok 72 should be called once

,ok 73 should not have been called more than once

,# setup

,ok 74 error should be null

,ok 75 error should be null

,# 19. can get the network status

,# teardown

,ok 76 network status should have certain non-empty properties

,# setup

,ok 77 error should be null

,ok 78 error should be null

,# 20. wifi peer is marked unavailable if announcements stop

,# teardown

,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined

,ok 79 host address should match

,ok 80 port should match

,ok 81 host address should be null

,ok 82 port should should be null

,# setup

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 83 error should be null

,ok 84 error should be null

,# 21. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-11 16:09:51.991 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
,2016-03-11 16:09:51.992 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:51.995 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
ok 85 Can call startListeningForAdvertisements without error

2016-03-11 16:09:51.999 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
2016-0,3-11 16:09:51.999 ThaliTest[1197:1772227] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-11 16:09:52.002 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,ok 86 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-11 16:09:52.233 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:52.233 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:52.234 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:52.235 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:52.237 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,# 22. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-11 16:09:52.447 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
,2016-03-11 16:09:52.448 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

2016-03-11 16:09:52.450 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
ok 87 Can call startListeningForAdvertisements without error

,2016-03-11 16:09:52.453 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}

,2016-03-11 16:09:52.455 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
,ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-11 16:09:52.842 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:52.842 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
2016-03-11 16:09:52.843 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:52.844 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:52.845 ThaliTest[1197:1772227] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-11 16:09:52.848 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,# 23. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-11 16:09:53.346 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:53.347 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:4
,2016-03-11 16:09:53.348 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
2016-03-11 16:09:53.349 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:4
2016-03-11 16:09:53.349 ,ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
ok 89 Can call startUpdateAdvertisingAndListening without error

,2016-03-11 16:09:53.351 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:53.353 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
2016-03-11 16:09:53.353 ThaliTest[1197:1772227] multipeer manager: stop client timer
,2016-03-11 16:09:53.355 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
ok 90 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-11 16:09:53.494 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:53.495 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:53.495 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:53.496 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:53.498 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,# 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-11 16:09:54.340 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:54.340 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:5
,2016-03-11 16:09:54.341 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
,2016-03-11 16:09:54.342 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:5
,2016-03-11 16:09:54.342 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
,ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-11 16:09:54.346 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
2016-03-11 16:09:54.347 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
2016-03-11 16:09:54.347 ThaliTest[1197:1772227] multipeer manager: stop client ti,mer
2016-03-11 16:09:54.347 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:6
2016-03-11 16:09:54.348 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
2016-03-11 16:09:54.349 ThaliTest[1197:,1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:6
2016-03-11 16:09:54.349 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
ok 92 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-11 16:09:54.815 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:54.816 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:54.816 ThaliTest[1197:1772227] multipeer manager: stop client timer
2016-03-11 16:09:54.817 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:54.818 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

2016-03-11 16:09:54.822 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,# 25. peerAvailabilityChange is called

,# teardown

,2016-03-11 16:09:55.324 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:09:55.325 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
,2016-03-11 16:09:55.326 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
2016-03-11 16:09:55.326 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7
2016-03-11 16:09:55.327 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
ok 93 Can call startUpdateAdvertisingAndListeningwithout error

,2016-03-11 16:09:55.329 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,
,2016-03-11 16:09:55.331 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements: success
,ok 94 Can call startListeningForAdvertisements without error

,2016-03-11 16:09:56.535 ThaliTest[1197:1771995] client: found new peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
,ok 95 peer must have peerIdentifier

,ok 96 peerIdentifier must be a string

,# setup

,2016-03-11 16:09:57.602 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening
,2016-03-11 16:09:57.603 ThaliTest[1197:1772227] THEMultipeerManager stopping peer
,2016-03-11 16:09:57.604 ThaliTest[1197:1772227] jxcore: stopAdvertisingAndListening: success
,2016-03-11 16:09:57.607 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements
2016-03-11 16:09:57.607 ThaliTest[1197:1772227] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}

,2016-03-11 16:09:57.611 ThaliTest[1197:1772227] jxcore: stopListeningForAdvertisements: success
,# 26. Can connect to a remote peer

,# teardown

,2016-03-11 16:10:13.383 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening
,2016-03-11 16:10:13.384 ThaliTest[1197:1772227] server: starting 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
,2016-03-11 16:10:13.385 ThaliTest[1197:1772227] multipeer manager: start client restart timer: 0x156c5d70
2016-03-11 16:10:13.387 ThaliTest[1197:1772227] THEMultipeerManager initialized peer 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8
2016-03-11 16:10:13.387 ThaliTest[1197:1772227] jxcore: startUpdateAdvertisingAndListening: success
,ok 97 Can call startUpdateAdvertisingAndListening without error

,2016-03-11 16:10:13.394 ThaliTest[1197:1772227] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}

2016-03-11 16:10:13.396 ThaliTest[1197:17722,27] jxcore: startListeningForAdvertisements: success
,ok 98 Can call startListeningForAdvertisements without error

,2016-03-11 16:10:15.420 ThaliTest[1197:1771995] client: found new peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
,2016-03-11 16:10:15.438 ThaliTest[1197:1772227] jxcore: connect 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
,2016-03-11 16:10:15.439 ThaliTest[1197:1772227] client session: connect
2016-03-11 16:10:15.439 ThaliTest[1197:1772227] client session: stateChange:0->1 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
,2016-03-11 16:10:16.497 ThaliTest[1197:1771995] multipeer session: reset timer
2016-03-11 16:10:16.497 ThaliTest[1197:1771995] server: rejecting invitation from 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC due to previous generation (80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:8 != 80B5A647-E8D7-4B4F-B7E0-C91D1B04D704:7)
,2016-03-11 16:10:16.508 ThaliTest[1197:1772772] client session: not connected 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
2016-03-11 16:10:16.508 ThaliTest[1197:1772772] client session: onLinkFailure: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC
2016-03-11 16:10:16.509 ThaliTest[1197:1772772] client session: disconnect
,2016-03-11 16:10:16.510 ThaliTest[1197:1772772] client session: stateChange:1->0 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:7
,2016-03-11 16:10:16.511 ThaliTest[1197:1772772] client session: fireConnectCallback: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC
,2016-03-11 16:10:16.511 ThaliTest[1197:1772772] jxcore: connect: fail: Peer disconnected
,not ok 99 Error from connect: Peer disconnected

,  ---

,    operator: fail

,  ...

,# setup

,2016-03-11 16:10:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:10:33.402 ThaliTest[1197:1771995] client: found updated peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:10:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:10:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:11:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:11:13.403 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:11:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:11:33.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:11:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:11:53.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:12:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:12:13.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:12:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:12:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:12:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:12:53.399 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:13:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:13:13.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:13:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:13:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:13:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:13:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:14:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:14:13.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:14:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:14:33.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:14:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:14:53.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:15:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:15:13.403 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:15:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:15:33.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:15:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:15:53.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:16:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:16:13.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:16:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:16:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:16:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:16:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:17:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:17:13.399 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:17:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:17:33.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:17:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:17:53.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:18:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:18:13.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:18:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:18:33.403 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:18:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:18:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:19:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:19:13.403 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:19:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:19:33.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:19:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:19:53.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:20:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:20:13.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:20:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:20:33.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:20:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:20:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:21:13.388 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:21:13.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:21:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:21:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:21:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:21:53.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:22:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:22:13.404 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:22:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:22:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:22:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:22:53.400 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:23:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:23:13.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:23:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:23:33.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:23:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:23:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:24:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:24:13.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:24:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:24:33.403 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:24:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:24:53.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:25:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:25:13.402 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:25:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:25:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:25:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:25:53.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:26:13.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:26:13.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:26:33.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:26:33.401 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8
,2016-03-11 16:26:53.387 ThaliTest[1197:1771995] multipeer manager: restart client
,2016-03-11 16:26:53.403 ThaliTest[1197:1771995] client: found existing peer: 14EE0FB2-BB37-4522-B2BD-C8DB4B45C5CC:8

```
