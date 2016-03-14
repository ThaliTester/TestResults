#### Test 6262501074dad8f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6262501074dad8f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/005F3D09-5C39-4FC0-9C71-1DC005ABFC90/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/005F3D09-5C39-4FC0-9C71-1DC005ABFC90/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6262501074dad8f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6262501074dad8f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51005"
,(lldb)     command script import "/tmp/005F3D09-5C39-4FC0-9C71-1DC005ABFC90/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 23:37:49.113 ThaliTest[1425:2260667] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/643C27B5-10F3-4BE1-8C94-EB9D35701735/Library/Cookies/Cookies.binarycookies
,2016-03-14 23:37:49.497 ThaliTest[1425:2260667] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 23:37:49.499 ThaliTest[1425:2260667] Multi-tasking -> Device: YES, App: YES
,2016-03-14 23:37:49.523 ThaliTest[1425:2260667] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 23:37:51.453 ThaliTest[1425:2260667] Using UIWebView
,2016-03-14 23:37:51.459 ThaliTest[1425:2260667] [CDVTimer][handleopenurl] 0.389040ms
,2016-03-14 23:37:51.467 ThaliTest[1425:2260667] [CDVTimer][intentandnavigationfilter] 7.012010ms
,2016-03-14 23:37:51.468 ThaliTest[1425:2260667] [CDVTimer][gesturehandler] 0.322044ms
,2016-03-14 23:37:51.468 ThaliTest[1425:2260667] [CDVTimer][TotalPluginStartup] 9.333014ms
,2016-03-14 23:37:58.598 ThaliTest[1425:2260667] Resetting plugins due to page load.
,2016-03-14 23:38:02.280 ThaliTest[1425:2260667] Finished load of: file:///var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/index.html
,2016-03-14 23:38:02.424 ThaliTest[1425:2260667] JXcore Cordova plugin initializing
,2016-03-14 23:38:02.424 ThaliTest[1425:2260884] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 23:38:15.578 ThaliTest[1425:2260884] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 23:38:15.578 ThaliTest[1425:2260884] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-14 23:38:15.579 ThaliTest[1425:2260884] jxcore: didRegisterToNative networkChanged
,2016-03-14 23:38:15.579 ThaliTest[1425:2260884] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/B3E68820-C966-481B-AF10-E822DA852541/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,2016-03-14 23:41:11.711 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:11.712 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,ok 38 error should be null

,ok 39 error should be null

,2016-03-14 23:41:11.719 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:11.720 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,ok 40 error should be null

,ok 41 error should be null

,# setup

,2016-03-14 23:41:11.877 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:11.878 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:11.879 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:11.880 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:11.881 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,ok 42 error should be null

,ok 43 error should be null

,# 13. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-14 23:41:12.142 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:12.143 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
,2016-03-14 23:41:12.145 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
,ok 44 error should be null

,ok 45 error should be null

,2016-03-14 23:41:12.159 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:12.160 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
,ok 46 error should be null

,ok 47 error should be null

,# setup

,2016-03-14 23:41:12.457 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:12.457 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:12.458 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:12.459 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:12.459 ThaliTest[1425:2260884] multipeer manager: stop client timer
,2016-03-14 23:41:12.461 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 48 error should be null

,ok 49 error should be null

,# 14. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-14 23:41:12.953 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:12.954 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:1
,2016-03-14 23:41:12.955 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
2016-03-14 23:41:12.956 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:1
,2016-03-14 23:41:12.958 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
,ok 50 error should be null

,ok 51 error should be null

,2016-03-14 23:41:12.988 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:12.988 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:12.989 ThaliTest[1425:2260884] multipeer manager: stop client timer
,2016-03-14 23:41:12.990 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:2
,2016-03-14 23:41:12.993 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
2016-03-14 23:41:12.994 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:2
2016-03-14 23:41:12.994 ,ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
,ok 52 error should be null

,ok 53 error should be null

,# setup

,2016-03-14 23:41:13.106 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:13.106 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:13.107 ThaliTest[1425:2260884] multipeer manager: stop client timer
2016-03-14 23:41:13.108 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
2016-03-14 23:41:13.109 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:13.111 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 54 error should be null

,ok 55 error should be null

,# 15. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-14 23:41:13.610 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:13.611 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:13.611 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,ok 56 error should be null

,ok 57 error should be null

,2016-03-14 23:41:13.617 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:13.617 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:13.618 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,ok 58 error should be null

,ok 59 error should be null

,# setup

,2016-03-14 23:41:13.972 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:13.972 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:13.973 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:13.974 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:13.976 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,ok 60 error should be null

,ok 61 error should be null

,# 16. #start should fail if called twice in a row

,# teardown

,ok 62 first call should succeed

,ok 63 first call should succeed

,ok 64 specific error should be returned

,# setup

,2016-03-14 23:41:15.752 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:15.753 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:15.753 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:15.754 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:15.756 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,ok 65 error should be null

,ok 66 error should be null

,# 17. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-14 23:41:16.215 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:16.216 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
,2016-03-14 23:41:16.218 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
,2016-03-14 23:41:16.238 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:16.239 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:3
,2016-03-14 23:41:16.240 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:3
2016-03-14 23:41:16.240 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
,ok 67 called only once

,ok 68 discovery state matches

,ok 69 advertising state matches

,# setup

,2016-03-14 23:41:16.542 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:16.543 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:16.543 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:16.545 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
2016-03-14 23:41:16.546 ThaliTest[1425:2260884] multipeer manager: stop client timer
,2016-03-14 23:41:16.549 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
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

,2016-03-14 23:41:20.465 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:20.466 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
,2016-03-14 23:41:20.467 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
,ok 85 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:20.473 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:20.473 ThaliTest[1425:2260884] multipeer manager: stop client timer
,2016-03-14 23:41:20.475 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,ok 86 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-14 23:41:20.741 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:20.741 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:20.742 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:20.743 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:20.744 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,# 22. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-14 23:41:21.246 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:21.247 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
,2016-03-14 23:41:21.249 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
ok 87 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:21.252 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:21.253 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
,ok 88 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-14 23:41:21.333 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:21.334 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:21.334 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:21.336 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:21.336 ThaliTest[1425:2260884] multipeer manager: stop client timer
,2016-03-14 23:41:21.339 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,# 23. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-14 23:41:22.000 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:22.001 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:4
,2016-03-14 23:41:22.002 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
,2016-03-14 23:41:22.003 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:4
,2016-03-14 23:41:22.004 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
ok 89 Can call startUpdateAdvertisingAndListening without error

,2016-03-14 23:41:22.006 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:22.007 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
2016-03-14 23:41:22.007 ThaliTest[1425:2260884] multipeer manager: stop client timer
2016-03-14 23:41:22.008 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,ok 90 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-14 23:41:22.348 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:22.349 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:22.349 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:22.351 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:22.352 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,# 24. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-14 23:41:22.525 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:22.526 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:5
,2016-03-14 23:41:22.527 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
2016-03-14 23:41:22.527 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:5
,2016-03-14 23:41:22.528 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
,ok 91 Can call startUpdateAdvertisingAndListening without error

,2016-03-14 23:41:22.530 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:22.531 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
2016-03-14 23:41:22.531 ThaliTest[1425:2260884] multipeer manager: stop client ti,mer
2016-03-14 23:41:22.532 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:6
,2016-03-14 23:41:22.537 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
2016-03-14 23:41:22.538 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:6
2016-03-14 23:41:22.539 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
ok 92 Can call startUpdateAdvertisingAndListening twice without error

# setup

,2016-03-14 23:41:22.856 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
2016-03-14 23:41:22.856 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:22.857 ThaliTest[1425:2260884] multipeer manager: stop client timer
,2016-03-14 23:41:22.857 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:22.859 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:22.861 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,# 25. peerAvailabilityChange is called

,# teardown

,2016-03-14 23:41:23.262 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
,2016-03-14 23:41:23.263 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
,2016-03-14 23:41:23.264 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
2016-03-14 23:41:23.264 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7
2016-03-14 23:41:23.265 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
,ok 93 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-14 23:41:23.267 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
,2016-03-14 23:41:23.269 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
ok 94 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:24.629 ThaliTest[1425:2260667] client: found new peer: A23A2191-9ACE-4296-8393-82BF95886094:7
,ok 95 peer must have peerIdentifier

,ok 96 peerIdentifier must be a string

,# setup

,2016-03-14 23:41:24.950 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening
,2016-03-14 23:41:24.951 ThaliTest[1425:2260884] THEMultipeerManager stopping peer
,2016-03-14 23:41:24.951 ThaliTest[1425:2260884] jxcore: stopAdvertisingAndListening: success
,2016-03-14 23:41:24.952 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements
,2016-03-14 23:41:24.956 ThaliTest[1425:2260884] multipeer manager: stop client timer
2016-03-14 23:41:24.959 ThaliTest[1425:2260884] jxcore: stopListeningForAdvertisements: success
,# 26. Can connect to a remote peer

,# teardown

,2016-03-14 23:41:25.369 ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening
2016-03-14 23:41:25.370 ThaliTest[1425:2260884] server: starting 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
,2016-03-14 23:41:25.371 ThaliTest[1425:2260884] multipeer manager: start client restart timer: 0x17ecd130
2016-03-14 23:41:25.372 ThaliTest[1425:2260884] THEMultipeerManager initialized peer 435ACF87-6352-482F-B5FA-1EDD8A011FA8:8
2016-03-14 23:41:25.373 ,ThaliTest[1425:2260884] jxcore: startUpdateAdvertisingAndListening: success
,ok 97 Can call startUpdateAdvertisingAndListening without error

,2016-03-14 23:41:25.376 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements
2016-03-14 23:41:25.378 ThaliTest[1425:2260884] jxcore: startListeningForAdvertisements: success
ok 98 Can call startListeningForAdvertisements without error

,2016-03-14 23:41:26.225 ThaliTest[1425:2260667] client: found new peer: A23A2191-9ACE-4296-8393-82BF95886094:7
,2016-03-14 23:41:26.243 ThaliTest[1425:2260884] jxcore: connect A23A2191-9ACE-4296-8393-82BF95886094:7
,2016-03-14 23:41:26.243 ThaliTest[1425:2260884] client: server will connect
2016-03-14 23:41:26.244 ThaliTest[1425:2260884] client session: reverseConnect
,2016-03-14 23:41:26.244 ThaliTest[1425:2260884] client session: stateChange:0->1 A23A2191-9ACE-4296-8393-82BF95886094:7
,2016-03-14 23:41:26.739 ThaliTest[1425:2260667] multipeer session: reset timer
,2016-03-14 23:41:26.739 ThaliTest[1425:2260667] server: rejecting invitation from A23A2191-9ACE-4296-8393-82BF95886094 due to previous generation (435ACF87-6352-482F-B5FA-1EDD8A011FA8:8 != 435ACF87-6352-482F-B5FA-1EDD8A011FA8:7)
,2016-03-14 23:41:26.796 ThaliTest[1425:2261324] client session: not connected A23A2191-9ACE-4296-8393-82BF95886094:7
2016-03-14 23:41:26.797 ThaliTest[1425:2261324] client session: onLinkFailure: A23A2191-9ACE-4296-8393-82BF95886094
2016-03-14 23:41:26.798 ThaliTest[1425:2261324] client session: disconnect
2016-03-14 23:41:26.798 ThaliTest[1425:2261324] client session: stateChange:1->0 A23A2191-9ACE-4296-8393-82BF95886094:7
,2016-03-14 23:41:26.799 ThaliTest[1425:2261324] client session: no connect callback (server initiated)
,2016-03-14 23:41:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:41:45.387 ThaliTest[1425:2260667] client: found updated peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:42:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:42:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:42:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:42:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:42:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:42:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:43:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:43:05.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:43:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:43:25.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:43:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:43:45.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:44:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:44:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:44:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:44:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:44:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:44:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:45:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:45:05.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:45:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:45:25.385 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:45:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:45:45.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:46:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:46:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:46:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:46:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:46:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:46:45.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:47:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:47:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:47:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:47:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:47:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:47:45.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:48:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:48:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:48:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:48:25.385 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:48:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:48:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:49:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:49:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:49:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:49:25.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:49:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:49:45.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:50:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:50:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:50:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:50:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:50:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:50:45.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:51:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:51:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:51:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:51:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:51:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:51:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:52:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:52:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:52:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:52:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:52:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:52:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:53:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:53:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:53:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:53:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:53:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:53:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:54:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:54:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:54:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:54:25.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:54:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:54:45.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:55:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:55:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:55:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:55:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:55:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:55:45.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:56:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:56:05.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:56:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:56:25.388 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:56:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:56:45.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:57:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:57:05.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:57:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:57:25.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:57:45.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:57:45.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:58:05.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:58:05.386 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:58:25.373 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:58:25.387 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8
,2016-03-14 23:58:45.372 ThaliTest[1425:2260667] multipeer manager: restart client
,2016-03-14 23:58:45.385 ThaliTest[1425:2260667] client: found existing peer: A23A2191-9ACE-4296-8393-82BF95886094:8

```
